<div align="center">
  <h1> Motivue </h1>
  <p>
    <strong>Training, Education & Fitness Methodology</strong>
  </p>
</div>

### About This Repository

This repository exists to share my work on fitness as a system—not just as workouts.

I am a long-term researcher and practitioner in China's fitness industry, focused on:

- Empowerment-first coaching models where clients eventually "graduate."
- Hypertrophy and strength training based on biomechanics and exercise physiology.
- Practical nutrition systems that balance science, results, and real-life enjoyment.

Here you will find my white paper and training philosophy—mostly my own thinking and experiments—that I use to guide my personal training and how I work with people around me.

### What’s Inside

- `WHITEPAPER.md`  
  Motivue Empowerment & Education Methodology – my diagnosis of the current private fitness industry and a complete model for client empowerment (English & Chinese, bilingual).

- `TRAINING_PHILOSOPHY.md`  
  Training Philosophy & First-Principles Fitness Guide – a structured explanation of my approach to training, nutrition, and behavior, including hypertrophy principles, fatigue management, macro-based nutrition, and the behavior systems behind sustainable change (English & Chinese, bilingual).

- External project: [`Motivue-Backend`](https://github.com/zmlAEQ/Motivue-Backend)  
  A backend I built to operationalise this philosophy in code. It includes:
  - A Bayesian readiness engine that fuses training load, HRV, sleep, biomarkers, Hooper scores, menstrual cycle signals and journals into a daily “readiness / fatigue” score.  
  - A baseline service that learns your personal normals (sleep, HRV, recovery ratios) and auto-updates them over time.  
  - A weekly report microservice where a multi‑agent LLM turns your readiness history into structured charts and narrative reviews.  
  The architecture is heavily informed by reading and synthesising insights from hundreds of sports science, HRV, and fatigue-management papers.

As this project evolves, I may add tools, templates, or open-source planning utilities built on top of this methodology.

---

### 关于本仓库

这个仓库，是我用来系统性地分享自己健身方法论的地方，而不只是训练计划的合集。

我长期自己研究并实践中国健身 / 私教行业，主要关注：

- 以“赋权”和“学员毕业”为终点的教学思路。  
- 建立在生物力学和运动生理学基础上的肌肥大与力量训练。  
- 在科学、效果和“吃得开心”之间取得平衡的饮食系统。

这里的内容，本质上是我自己的思考与实践记录——既给自己用，也分享给任何对这套体系感兴趣的人。

### 仓库内容概览

- `WHITEPAPER.md`  
  《Motivue 赋权与教育方法论白皮书》——对当前私人健身行业的结构性诊断，以及我提出的完整“赋权模型”（中英文双语）。

- `TRAINING_PHILOSOPHY.md`  
  《训练理念与第一性原理健身指南》——系统讲解我的训练、饮食与行为框架，包括肌肥大原理、疲劳管理、宏量营养与自由饮食、以及如何把这些变成可持续的生活方式（中英文双语）。

- 外部项目：[`Motivue-Backend`](https://github.com/zmlAEQ/Motivue-Backend)  
  我自己开发的一套后端，用来把这里的理念真正落地到“每天怎么练、怎么恢复”的层面，主要包含：  
  - 一个贝叶斯准备度 / 疲劳引擎，融合训练量、HRV、睡眠、生理指标、Hooper 指数、月经周期和训练日记等多源数据，给出每日 readiness 分数。  
  - 一个基线服务，长期学习你的“个人正常值”（睡眠、HRV、恢复比值等），并自动更新。  
  - 一个周报微服务，由多智能体 LLM 把一周的 readiness 历史转化为图表和文字复盘。  
  整体架构是我在阅读并消化上百篇运动科学、HRV 和疲劳管理论文之后设计出来的，用来作为这套方法论在数据与分析层的支撑。

后续我可能会在此基础上，增加一些基于该方法论的工具、模板或开源规划小工具。
