# 👋 Hi, I'm Liu Shuchao

> *“Give me a place to stand on, and I can move the earth.”*

## 🚀 About Me

I am a Master’s student in **New-Generation Electronic Information Technology** at Beijing Institute of Technology, with a strong interest in **AI Infra, Embedded Systems, and High-Performance Computing**.

I enjoy building end-to-end systems that bridge **hardware, systems software, and AI algorithms**, with hands-on experience across embedded deployment, model optimization, and large-scale communication frameworks.

---

## 🎓 Education

- 🎓 **Beijing Institute of Technology** (2024.09 - Present)  
  Master, New-Generation Electronic Information Technology  

- 🎓 **Wuhan Institute of Technology** (2020.07 - 2024.06)  
  Bachelor, Information Engineering  

---

## 🧠 Skills & Interests

- 💻 Programming: C / C++ / Python
- 🧩 Systems: Linux, Embedded Systems, Cross-compilation
- ⚡ AI Deployment: OpenCV, YOLOv8, NPU inference optimization
- 🔗 High-Performance Computing: NCCL, Collective Communication (AllReduce / AllGather)
- 🧱 Architecture: CUDA/NVML abstraction, hardware-software decoupling
- 🧪 Embedded Platforms: RISC-V, HiFive, heterogeneous acceleration
- 🛠 Toolchain: Makefile, GCC, cross-platform build systems

---

## 🧩 Project Experience

### 🚗 Real-time Road Object Detection System (Embedded + NPU)
**Team Leader | 2025.04 - 2025.06**

- Built a real-time object detection system based on **RISC-V HiFive Premier P550**
- Deployed **YOLOv8s** with model quantization and compilation via ENNP AI toolchain
- Integrated **OpenCV video pipeline** for real-time camera streaming
- Leveraged onboard **NPU (EIPS200B)** for acceleration, achieving **80.3 FPS inference**

Key achievements:
- End-to-end embedded system bring-up (bootloader, OS, drivers)
- Cross-compilation and hardware debugging via UART/Ethernet
- C++ implementation of full inference pipeline with low-latency design

---

### 🛰 Radar & Infrared Detection Simulation System
**C++ System Design Project | 2024.09 - 2025.03**

- Designed a modular simulation system for radar and infrared seeker modeling
- Implemented target detection, tracking, interference, and strategy modules
- Simulated complex environments including **jamming and interception logic**
- Built using object-oriented C++ architecture for scalability and extensibility

---

## 🧑‍💻 Internship Experience

### 🧠 AI Infra Engineer Intern  
**Tsinghua University Brain-Inspired Computing Center / Tanwei Xinlian**  
2025.07 - 2025.09

Focus: **Decoupling NCCL from NVIDIA hardware ecosystem for cross-platform portability**

Key contributions:

- 🧩 **NCCL Architecture Refactoring**
  - Designed a hardware abstraction layer (`TWwrap`)
  - Unified CUDA Runtime / Driver / NVML interfaces
  - Used `void*` + macro dispatch for cross-platform API abstraction
  - Reserved interfaces for domestic GPU/NPU integration

- ⚙️ **Build System & Cross-platform Support**
  - Reconstructed Makefile system to remove hardware coupling
  - Enabled conditional compilation for multi-backend support
  - Achieved successful build in pure g++ environment

- 🔄 **Collective Communication Validation**
  - Understood and validated AllReduce / AllGather mechanisms
  - Verified correctness of decoupled architecture via ring-based communication
  - Ensured end-to-end communication integrity

---

## 🏆 Awards

- 🥇 National First Prize – Provincial Mathematics Competition (Hubei)
- 🥈 National Third Prize – IC Innovation & Entrepreneurship Competition
- 🥉 National Third Prize – RoboCup / Robot Developer Competition
- 🧠 Provincial Third Prize – Large Model Agent Innovation Challenge
- 🎓 Outstanding Academic Scholarship (Top-tier)
- 📜 CET-4 / CET-6

---

## 📫 Contact

- 📧 Email: 17615784286@163.com  
- 📱 Phone: 17615784286  
- 📍 Location: Beijing, China  

---

## ⚡ Motto

> Build systems. Break boundaries. Bridge hardware and intelligence.
