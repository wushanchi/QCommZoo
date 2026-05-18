# 01-Theory / 理论基础

本目录收录量子通信相关的经典论文、学术资料和基础科普内容。

## 分类说明

- **经典论文** — 量子通信领域的开创性研究论文（PDF格式）
- **学术资料** — 综述文章、教材章节、课程讲义
- **基础科普** — 面向初学者的入门资料

## 文件命名规范

`[年份]-[作者/机构]-[标题].pdf`

## 资料索引

### 2026 年重大研究突破

#### 中国-南非 12,900km 量子安全通信（2025年3月）
- **团队**：中国科学技术大学（USTC）领导的国际团队
- **卫星**：Jinan-1 微纳卫星
- **突破**：首次实现中国-南非实时量子密钥分发（QKD）
- **技术**：紧凑型地面站 + 微型卫星
- **意义**：为全球卫星 QKD 服务奠定了基础

#### QKD 技术路线：DV-QKD 与 CV-QKD 对比（2026-03）
- **DV-QKD（离散变量）**：单光子级别检测，成熟度高，适合长距离
- **CV-QKD（连续变量）**：利用光场 quadratures 编码，兼容经典光通信设备
- **中国进展**：国盾量子推动 CV-QKD 商业化，量子通信设备已部署
- **趋势**：两者互补，CV-QKD 在高信噪比城域场景有优势

#### BB84 协议获 2026 年图灵奖
- **作者**：Charles Bennett 与 Gilles Brassard
- **年份**：1984年提出
- **荣誉**：2026 年获计算机界最高荣誉
- **贡献**：开创量子密码学领域

#### Imperial College 量子网络里程碑
- **突破**：首次实现量子信息的产生、存储、检索
- **技术**：使用常规光纤传输量子数据
- **合作**：Imperial College London、Southampton、Stuttgart
- **意义**：量子网络关键步骤

### 经典论文与开创性工作

#### BB84 协议（1984）
- [BB84 原始论文](https://ieeexplore.ieee.org/document/1055394) - Bennett & Brassard，1984年
- **核心**：利用量子态制备和测量实现安全密钥分发
- **安全性**：基于量子不可克隆定理和测量坍缩

#### E91 协议（1991）
- [E91 协议](https://link.springer.com/article/10.1007/BF00191318) - Artur Ekert，1991年
- **核心**：基于量子纠缠的密钥分发
- **特点**：利用贝尔不等式检验安全性

#### 量子隐形传态
- [Quantum Teleportation](https://www.nature.com/articles/37566487) - Bennett et al., 1993年
- **原理**：利用纠缠将量子态传输到远端
- **应用**：量子通信、量子网络

#### 量子密集编码
- [Quantum Dense Coding](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.69.2881) - Bennett & Wiesner，1992年
- **原理**：利用纠缠增加经典信息容量

### 量子通信理论

#### 量子密钥分发（QKD）理论
- **安全基础**：量子力学基本原理
  - 量子不可克隆定理
  - 海森堡不确定性原理
  - 测量导致态坍缩
- **信息论安全**：量子密钥分发可实现信息论安全（无条件安全）

#### 量子纠缠理论
- **纠缠态**：贝尔态（EPR 对）
- **纠缠度量**：纠缠熵、Concurrence
- **纠缠操作**：贝尔态测量、纠缠交换

#### 量子中继理论
- **量子中继器**：克服光纤损耗
- **纠缠交换**：延长纠缠距离
- **纠缠纯化**：提高纠缠质量
- **量子存储**：存储量子态

### 量子网络理论

#### 量子互联网
- [Quantum Internet Initiative](https://www.quantuminternet.it/) - 欧洲量子互联网计划
- **目标**：连接量子计算机、传感器、用户
- **核心**：量子纠缠分发网络

#### 量子网络架构
- **接入层**：量子终端（QKD 设备）
- **传输层**：量子中继器、光纤
- **应用层**：量子计算、量子传感

### 综述与教程

#### 量子通信综述
- [Quantum Communication Networks](https://link.springer.com/chapter/10.1007/978-3-030-62938-0_6) - Springer，量子通信网络设计与仿真
- [量子通信原理](https://blog.51cto.com/u_12868/14471310) - QKD 与 BB84 协议详解

#### 量子密码学
- [Post-Quantum Cryptography](https://csrc.nist.gov/projects/post-quantum-cryptography) - NIST 后量子密码学标准
- [量子安全标准](https://www.idquantique.com/quantum-safe-security/) - ID Quantique 量子安全解决方案

### 学术会议与期刊

- [QIP 2026](https://qip2026.info/) - 量子信息处理顶级会议
- [Quantum Journal](https://quantum-journal.org/) - 开放获取量子科学期刊
- [Nature Physics](https://www.nature.com/nphys/) - 量子物理前沿研究

### 量子通信公司技术博客

- [ID Quantique Blog](https://www.idquantique.com/blog/) - 量子安全最新进展
- [Qunnect Blog](https://www.qunnect.com/blog) - 量子网络实验进展

---

*最后更新: 2026-05-12*
