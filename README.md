# AES-on-FPGA
这是2020年新工科联盟-Xilinx暑期学校（Summer School）的项目。
#项目简介
高级加密标准AES(advanced encryption standard)于2001年提出，用于取代早期DES加密算法，是目前广泛应用的加密算法，是对称密码算法较为流行的一种。目前有多种软件方案实现AES算法，其优先考虑加密速度与吞吐量。而在穿戴设备如手环中更重要的是低功耗，低资源，小面积。
就此，通过Verilog HDL硬件描述语言来实现AES加密算法，通过模块间的调用，实现代码的高效利用，减少芯片面积，降低能耗。同时，通过硬件来实现密钥模块，可保证在外界无密钥的明文流动，增强安全性。最终通过仿真代码来测试电路的正确性。
#项目技术方案
使用Vivado 2018.3进行综合，实现，仿真，上传到FPGA开发板。
使用Verilog HDL硬件描述语言来实现AES加密算法。
使用状态机控制外部信号输入和内部加密流程。
模块预计分为数据读取，密钥扩展，加密，顶层。
#参考资料
https://github.com/mematrix/AES-FPGA