---
layout: page
title: Research
permalink: /projects/
description: My research path began with hardware security primitives and progressed to the system level. FPGA Virtualization is a key aspect of my Ph.D. research. My current research direction will focus more on the contribution of hardware systems to security and privacy. I will continue to explore truly valuable cloud computing systems from hardware, system, and software levels.
nav: true
nav_order: 2
horizontal: false
---

1. [FPGA Virtualization System](#FPGA_Vir)
2. [Hardware Security](#Hw_sec)
3. [Trustworthy AI Acceleration and Optimization](#ai)


## FPGA Virtualization System: Hardware-Oriented Threats and Mitigations <a name="FPGA_Vir"></a>
Technologies for cloud virtualization are extensively utilized in public cloud services. Currently, there is significant focus in both industry and academic research on virtualization technologies involving FPGA-based cloud instances.

Our vision is to develop a commercial prototype of a Virtualized FPGA, further enhancing hardware acceleration support for internet applications. Considering the distinct system architecture of cloud FPGA instances, as opposed to traditional CPU/GPU-based cloud instances, and the hardware programmability of FPGAs, our focus begins with addressing the security challenges of multi-tenant FPGAs. We explore potential attack models and specific, commonly used attack methods, such as those in AI inference applications, to generate ideas for the design of Cloud FPGA hypervisors.

##### **Featured publications**
- Identified potential attacks within FPGA virtualization systems that exploit hardware programming, including but not limited to, attacks like stealing sensitive information through long-wire methods, fault injection via power distribution networks (PDN), side-channel analysis, and the denial-of-service attack.
  - [FPGAPRO: A Defense Framework Against Crosstalk-Induced Secret Leakage in FPGA](https://dl.acm.org/doi/abs/10.1145/3491214) (**TODAES**)
  - [Deep-Dup: An Adversarial Weight Duplication Attack Framework to Crush Deep Neural Network in Multi-Tenant FPGA](https://www.usenix.org/system/files/sec21-rakin.pdf) (**USENIX Security**)

- Engineered protective measures to counter the above attacks and incorporate these defenses into the hypervisor of FPGA virtualization systems.
  - [A Cautionary Note on Building Multi-tenant Cloud-FPGA as a Secure Infrastructure](https://ieeexplore.ieee.org/document/9974230?denied=) (**FPT**)
  - [A Quantitative Defense Framework against Power Attacks on Multi-tenant FPGA](https://ieeexplore.ieee.org/abstract/document/9256466) (**ICCAD**)

- Developed specific defensive strategies for applications, such as protecting deep neural network (DNN) inference processes from the above attacks.
  - [DeepShuffle: A Lightweight Defense Framework against Adversarial Fault Injection Attacks on Deep Neural Networks in Multi-Tenant Cloud-FPGA](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a034/1RjEa9WUlPi) (**S&P**)

<br>


## Hardware Security <a name="Hw_sec"></a>
My main contributions in the field of hardware security are focused on the development of hardware security primitives.

##### **Featured publications**
- Designed a True Random Number Generator (TRNG) hardware circuit based on Chaotic Cellular Automata Topology.
  - [A High-Performance and Secure TRNG Based on Chaotic Cellular Automata Topology](https://ieeexplore.ieee.org/abstract/document/9185072) (**TCAS-I**)

- Utilized Physical Unclonable Function to design FPGA-based Trust Enclave.
  - [SGX-FPGA: Trusted Execution Environment for CPU-FPGA Heterogeneous Architecture](https://ieeexplore.ieee.org/abstract/document/9586207) (**DAC**)

- Developed a defense method for DNN inference against RowHammer attacks. 
  - [HammerDodger: A Lightweight Defense Framework against RowHammer Attack on Deep Neural Networks](https://ieeexplore.ieee.org/abstract/document/10247671) (**DAC**)

<br>

## Trustworthy AI Acceleration and Optimization <a name="ai"></a>
The enactment of stricter privacy laws and the awakening of public awareness towards privacy protection demand higher levels of privacy and security for cloud services, urgently requiring the development of a reliable, secure computing accelerator. This research field aims to apply methods such as **Multipart Computing (MPC)**, **Fully Homomorphic Encryption (FHE)**, and **Hardware Enclave** technologies to enable a trustworthy AI accelerator in the cloud, addressing critical privacy and security concerns.

##### **Featured publications**
- [AQ2PNN: Enabling Two-party Privacy-Preserving Deep Neural Network Inference with Adaptive Quantization](https://dl.acm.org/doi/10.1145/3613424.3614297) (**MICRO**)
  [LinGCN: Structural Linearized Graph Convolutional Network for Homomorphically Encrypted Inference](https://openreview.net/pdf?id=5loV5tVzsY) (**NeurIPS**)

<br>