***Note: This is not my resume. It's ought to be an all-in-one information aggregation used to generate my resume. For my resume, please visit [here](Resume.pdf).***

# Jerry (Yuan) Zhou

### CS Undergraduate @ UC Berkeley (Class of 2020)

## About

I'm interested in the underlying structures and low level applications of computing machines, particularly Operating Systems, Instruction Set Architectures, Integrated Circuits, Networking, and Computer Security. I'm also able to develop high-quality user applications, be it native apps or websites.

## Personal Information

- Phone  
    (510) 761-4040
- E-mail  
    [yvbbrjdr@berkeley.edu](mailto:yvbbrjdr@berkeley.edu)
- GitHub
    - [https://github.com/yvbbrjdr](https://github.com/yvbbrjdr)
    - [https://github.com/GreaterFire](https://github.com/GreaterFire)
- LinkedIn
    - [https://yvb.moe/in](https://yvb.moe/in)

## Awards

- **Regional Second Place** in *Division II, ACM-ICPC*  
    Nov 2019
- **Site First Place** in *Division II, ACM-ICPC*  
    Nov 2017
- **First Prize** in *National Olympiad of Informatics in Province, China Computer Federation*  
    Dec 2014

## Skills

- Linux
- Docker
- Kubernetes
- C/C++/Golang
- Java/Python/TypeScript
- SQL
- CI/CD
- Release Engineering
- Complicated System Design
- Network Protocol Design
- Computer Graphics and Parallelization
- Digital Signal Processing

## Education

- **University of California, Berkeley**  
    Aug 2017 - May 2020  
    Berkeley, CA  
    B.A. Computer Science  
    GPA: 3.854 (Major GPA: 3.976 (Upper Div. GPA: 4.000))  
    Relevent Courses:
    - CS 152: Computer Architecture (P)
    - CS 162: Operating Systems (A)
    - EECS 151: Digital Design and IC (A)
    - CS 161: Computer Security (P)
    - CS 184: Computer Graphics (A+)
    - CS 168: Computer Network (A+)
    - CS 182: Deep Neural Networks (P)
    - CS 188: Artificial Intelligence (A+)
    - CS 186: Databases (A+)
    - CS 170: Algorithms (A+)
    - CS 70: Discrete Math (A+)
    - CS 61C: Machine Structures (A+)
    - CS 61B: Data Structures (A+)

## Experience

### Work

- **Software Engineering Intern** at *Kelda Inc*  
    Jun 2019 - Aug 2019  
    Berkeley, CA
    - Built a scalable application in Golang that makes development in Kubernetes clusters easier for microservice developers (30k+ lines of code).
    - Designed and engineered a feature that makes it easy to live update Docker images in the cluster.
    - Created a framework that automatically provisions and destroys Kubernetes clusters on Google Compute Engine for the integration tests of the product.
- **Software Engineering Intern** at *App-Ark Education*  
    2017  
    Shanghai, China
    - Designed a student management system with *Laravel*.
- **Software Engineering Intern** at *Bigger Lab*  
    2017  
    Shanghai, China
    - Architected the network topology for the staff and students.
    - Designed creative projects for students.

### Research

- **Undergraduate Research Assistant** at *Berkeley NetSys Lab* with **Professor Scott Shenker**  
    Feb 2019 - Oct 2019  
    Berkeley, CA
    - Gathered metrics about the overhead of the Linux thread scheduler.
    - Explored potential ways to optimize chained packet-based software.

### Teaching

- **Reader** at *UC Berkeley CS 70 - Discrete Math and Probability*  
    Jan 2019 - May 2019  
    Berkeley, CA
    - Graded homework for ~700 students in the class.
    - Helped answer student questions in homework parties and office hours.
- **Academic Intern** at *UC Berkeley CS 61C - Machine Structures*  
    Aug 2018 - Dec 2018  
    Berkeley, CA
    - Graded labs for 80 students each week.
    - Helped answer student questions in office hours.

## Selected Projects

- **Trojan-GFW**: [https://github.com/trojan-gfw/trojan](https://github.com/trojan-gfw/trojan)  
    Oct 2017 - Present  
    C++  
    A proxy server and client that aims at bypassing the Great Firewall of China. It can disguise itself as an HTTPS server to avoid the active probe of the Great Firewall. The server performs a TLS handshake with whatever client that connects to it and, depending on whether the client sends a correct password, acts like a proxy server or an HTTPS server.
    - A fast and lightweight obfs web proxy aiming at penetrating DPI (Deep Packet Inspection) firewalls.
    - Features anti active and passive protocol detection.
    - Received **10k+ stars** on GitHub, has thousands of users, and gained its entrance into major Linux distributions, such as Debian and Arch Linux.
- **Relativistic Ray Tracer**: [https://yvb.moe/relativistic-ray-tracer/](https://yvb.moe/relativistic-ray-tracer/)  
    Apr 2019 - May 2019  
    C++  
    Normally when we perform path tracing, we shoot a straight ray from the camera directly to the scene. But if we want to simulate the bending of light due to general relativity, the light ray is curved so we can't perform the BVH intersection algorithm as we normally could. The way this project deal with curved light rays is it split the light ray into small segments of microrays. We integrate the light ray using 4th order runge kutta on the schwarzschild metric as the ray progresses and perform BVH intersection with these microrays. In this way we can find the intersection between the curved light ray and the scene.
    - A progressive path tracer that can simulate bending of light caused by massive objects due to general relativity.
    - Features wide spectrum and Doppler Redshift.
    - Invited to present to the EECS department.
- **procon**: [https://github.com/yvbbrjdr/procon](https://github.com/yvbbrjdr/procon)  
    Jul 2019 - Aug 2019  
    Python
    - A userspace Nintendo Switch Pro Controller Linux device driver.
    - Features stick calibration, accelerometer, gyroscope, and rumbling support.
- **RISC-V Processor**: [https://ucb.yvb.moe/Fall 2019/EECS 151/report.pdf](https://ucb.yvb.moe/Fall%202019/EECS%20151/report.pdf)  
    Oct 2019 - Dec 2019  
    Verilog
    - A functioning 3-stage RV32I core with a CPI of 1 running at 75 MHz on a Zynq-7000 Xilinx FPGA.
    - Features BIOS, loadable user programs, ability to communicate with a host computer via UART, memory-mapped user I/O, and a memory-mapped subtractive synthesizer.
