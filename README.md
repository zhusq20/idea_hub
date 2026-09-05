# Idea Hub

多个研究项目的集合。每个项目在 `projects/` 下独立维护自己的目标、研究材料、实验设计与后续实现。

## 项目索引

| 项目 | 核心问题 | 状态 |
| --- | --- | --- |
| [Loop Transformer Distillation](projects/loop-transformer-distillation/) | 将 Qwen3 的显式 CoT 蒸馏为循环隐式推理，借鉴 dLLM 后训练改善成本—准确率前沿 | 研究设计 |

## 组织方式

```text
idea_hub/
├── README.md
└── projects/
    └── <project-name>/
        ├── README.md
        └── docs/
```

每个子项目的 `README.md` 是入口，说明问题、目标、当前状态和材料位置。文档放在项目自己的 `docs/` 下；代码、配置和实验记录随项目进展在该子项目内添加。新增项目时，在本页索引中加入对应条目。

研究材料应明确区分已发表结果、设计推演和实际测量结果。
