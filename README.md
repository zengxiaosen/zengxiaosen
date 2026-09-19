### 曾晓森 (Xiaosen Zeng)

中信集团 · 中信证券 VP，10 年+ 金融科技、支付基础架构、云原生与 AI 工程经验。此前在腾讯微信支付负责基础架构相关工作，也在阿里巴巴大文娱、阿里妈妈、阿里健康等业务有研发经历。

我长期关注同一类问题：如何把前沿技术真正落到高可靠生产系统中，包括大模型 / Agent、联邦学习、深度学习、多模态、区块链、软件定义网络，以及支撑金融、电网、通信等行业场景的分布式系统。

#### 经历

- **中信集团 · 中信证券** (2024–至今) — VP。负责/推进金融自营、机构经纪、清算结算、AI 与前沿技术研究相关工作
- **腾讯 · 微信支付** (2019–2024) — 基础架构。负责生活缴费、支付分、微信支付商户中台、混沌工程、故障演练与自研上云相关工作
- **阿里巴巴** (实习) — 阿里大文娱、阿里妈妈 (2016–2017)，阿里健康 (2018)

#### 中信集团 · 中信证券

- **全球自营业务研发** — 作为技术 Leader，推进集团金融自营业务条线全资产清算簿记系统落地，覆盖 FX Spot、FX Forward、FX Swap、NDF、Options、IRS、CCS、SBL 等业务。建设中台交易簿记、风控计量、估值损益、Netting、后台交易结算等链上化能力，接入市场数据、Holiday、Bloomberg 等外部与内部系统，构建自研一体化全资产中后台清结算系统，逐步降低条线业务对 Calypso 的依赖。
- **机构经纪业务清算体系研发** — 基于云原生技术推进全球股票中台自研落地，支撑数据安全可控、防篡改与应用层弹性伸缩。完成中台多 Box 拆分，以及 Charge、Allocation、Confirmation、Block Combine、Block Split 等核心能力自研，配套 Scenario Test、CI/CD 与测试环境流量转发模型，测试覆盖率超过 95%，保障生产稳定运行。
- **机构经纪业务结算体系升级** — 作为技术 Leader 推进全球股票后台系统 SYN 的业务升级，优化基于 TIBCO 的老 Adaptor 与后台 SYN 系统，主导静态数据迁移、协议升级、DB 升级、生产并行测试、Spawn Trade 分析、Trade Flow 分析等工作，推动 CLSA、JV 等全球实体后台系统能力建设。
- **BOP 金融清算操作系统集成** — 推动邮件识别、资金表自动化、公司行为自动化、保证金自动化等多系统一体化，提升清算流程灵活性、资金清算结算自动化能力与运营效率。
- **前沿金融科技研究** — 持续开展区块链、联盟链、稳定币、稳定币脱锚风险、香港稳定币政策、量化金融、大模型、深度学习、多模态、端侧 AI、6G 与高通芯片生态等方向研究，并将研究成果沉淀到论文、工程原型与业务方案中。

#### 腾讯 · 微信支付

- **微信云助业务支付中台系统** — 作为技术骨干，支撑云助相关支付业务研发，负责业务建模与链路设计，覆盖支付、订单、退款、结算、分润、对账等核心子域；推进支付平台与统一接入系统的架构优化，支撑日常海量业务稳定运行。
- **微信支付商户产品核心系统** — 作为技术 Leader，面向行业应用和商户产品，支撑动态策略、商户健康度、风险评估与服务治理等能力建设；基于 Svrkit、TDSQL、CMQ、Docker、Kubernetes 等技术栈提升核心链路稳定性与接入效率。
- **混沌工程与故障演练平台** — 主导故障注入、演练控制、演练治理、风险防控和演练闭环能力建设，将故障演练从人工流程推进为平台化、体系化能力，提升微信支付核心系统对网络故障、框架故障、小程序故障、DB 故障、组件故障等复杂场景的风险应对能力。
- **支付分数据仓库与经营分析** — 参与构建微信支付分数据仓库与多维业务报表，支撑用户画像、临时表、MapJoin 等数据处理与分析任务，为业务发展、运营决策和指标治理提供数据支持。
- **自研上云与基础架构演进** — 参与微信支付在疫情期间的自研上云与弹性治理实践，支撑在线会议等大规模业务上云，提升资源弹性、部署效率与工程交付稳定性。

#### 研究方向

- **大模型与 Agent** — 预训练、后训练 (SFT / RLHF / RLVR)、强化学习、深度学习、Agent 架构与 AI 产品工程化
- **多模态与端侧智能** — 多模态建模、端侧 AI、高通芯片生态、工业场景 AI 落地
- **联邦学习与隐私计算** — 面向跨机构数据不可汇总场景的隐私保护训练、模型协同与安全评估
- **网络与安全** — 软件定义网络 (SDN)、DNS、网络模拟、网络流量智能分析与模拟、软件定义网络与安全、区块链与安全
- **行业落地** — 金融清结算、量化金融、稳定币与区块链、电网故障诊断、知识图谱、6G

#### 国家项目

- **国家重点研发计划** — 编号：2016YFB0800302。参与自主研发“多域网络互联安全控制关键技术及系统”，面向数据中心网络构建“国家空天地一体化系统”。基于 OVS 构建流量二层转发平面，基于 OpenDaylight / ONOS 构建路由控制平面，并围绕网络链路拥塞关键影响因素设计控制平面负载均衡路由算法，最终将算法 SDK 集成到 SDN 系统，提升数据中心网络负载均衡与突发流量应对能力。
- **国家科技部重大专项** — 编号：2012BAH45B01。基于 DPDK 加速技术提升 DAQ 网络流量收发性能，基于 Snort 多模匹配技术实现攻击流量识别与生成，通过应用层协议攻击检测模块动态库拆分支持检测协议自定义选择，并基于思博伦仪表进行性能评审，验证系统可在 10Gbps 背景流下完成攻击流量识别。

#### 成果与荣誉

- 国家金融行业证券从业资格证书
- 科研论文 10+ 篇，参与国家重大专项 2 项
- 腾讯公司级技术突破奖：微信混沌工程 + 故障演练 PMC
- 腾讯公司级管理突破奖：微信小团队实践管理突破奖
- 腾讯公司级自研上云奖：疫情期间支撑在线会议等大量业务上云
- 移动互联网安全技术国家工程实验室相关项目经历
- 国家一等奖学金、国家二等奖学金

#### 论文

- **Construction and Inference Method of Knowledge Graph for Power Grid Fault Diagnosis Based on Federated Deep Learning** — IEEE ICCECT 2026 · [Semantic Scholar](https://www.semanticscholar.org/paper/96a48afa281a4b5362f54382c853d6f233265b82)
- **Blockchain Quantitative Model Training Method Integrating Image Processing and Federated Learning: Asset Price Prediction for Multi-Institution Privacy Protection** — IEEE ICPEGE 2026 · [Semantic Scholar](https://www.semanticscholar.org/paper/b51ff74860d9e1afb32ec5363d80a2dfb314185b)
- **An Effective Load Balance Using Link Bandwidth for SDN-Based Data Centers** — LNCS, Springer 2019 · [10.1007/978-3-030-24268-8_24](https://doi.org/10.1007/978-3-030-24268-8_24)

#### 专利

均为腾讯微信支付期间申请：

- [**业务稳态检测方法及系统**](https://xueshu.baidu.com/s?wd=%E4%B8%9A%E5%8A%A1%E7%A8%B3%E6%80%81%E6%A3%80%E6%B5%8B%E6%96%B9%E6%B3%95%E5%8F%8A%E7%B3%BB%E7%BB%9F%20%E6%9B%BE%E6%99%93%E6%A3%AE) — 面向微信支付核心链路的服务稳态检测、混沌工程与故障演练治理能力
- [**支付一致性领域数据处理方法、装置、计算机可读存储介质和计算机设备**](https://xueshu.baidu.com/s?wd=%E6%95%B0%E6%8D%AE%E5%A4%84%E7%90%86%E6%96%B9%E6%B3%95%E3%80%81%E8%A3%85%E7%BD%AE%E3%80%81%E7%94%B5%E5%AD%90%E8%AE%BE%E5%A4%87%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%8F%AF%E8%AF%BB%E5%AD%98%E5%82%A8%E4%BB%8B%E8%B4%A8%20%E6%9B%BE%E6%99%93%E6%A3%AE) — 支撑支付平台一致性服务、消息去重放与账务链路一致性治理
- [**支付风控领域数据处理方法、装置、电子设备及计算机可读存储介质**](https://xueshu.baidu.com/s?wd=%E6%95%B0%E6%8D%AE%E5%A4%84%E7%90%86%E6%96%B9%E6%B3%95%E3%80%81%E8%A3%85%E7%BD%AE%E3%80%81%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%8F%AF%E8%AF%BB%E5%AD%98%E5%82%A8%E4%BB%8B%E8%B4%A8%E5%92%8C%E8%AE%A1%E7%AE%97%E6%9C%BA%E8%AE%BE%E5%A4%87%20%E6%9B%BE%E6%99%93%E6%A3%AE) — 面向支付风控与数据处理场景的数据质量、链路治理与工程化处理能力

#### 技术栈

Java · Go · Scala · Python · Flink · Spark · Kafka · Kubernetes · Docker · TDSQL · TIBCO · OVS · OpenDaylight · ONOS · DPDK · Snort · LLM · Federated Learning · Blockchain

#### 部分仓库

- [**flinkMultiStreamOptimization**](https://github.com/zengxiaosen/flinkMultiStreamOptimization) — Flink 多流 Join 的数据丢失与性能问题修复
- [**kafka-fault-tolerant**](https://github.com/zengxiaosen/kafka-fault-tolerant) — Kafka 元数据一致性，Spark 到 Oracle 数据链路实践

#### 教育

北京邮电大学 计算机科学 硕士 (2016–2019)

---

[![ORCID](https://img.shields.io/badge/ORCID-0000--0002--1413--5411-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0000-0002-1413-5411)
