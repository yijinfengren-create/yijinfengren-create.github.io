---
title: "基于WOE–IV特征筛选与集成学习的银行产品认购预测研究——面向电话营销客户分层的实证分析"
collection: publications
category: course  #模板为manuscripts
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: '基于22500条银行电话营销数据，采用WOE-IV特征筛选，对比逻辑回归与随机森林模型，验证随机森林在客户分层与营销名单排序任务上的优越性能。'
date: 2026-08-01
venue: ''
slidesurl: 'https://yijinfengren-create.github.io/files/course_paper_bank_subscription_prediction.pdf'
paperurl: 'https://yijinfengren-create.github.io/files/course_paper_bank_subscription_prediction.pdf'
citation: ''
---

## 摘要

本文以客户是否认购银行产品为目标变量，对 22500 条营销记录开展客户分层。数据无 NaN 缺失，排除标识字段 id 后无重复样本，认购率为 13.12%。实验按目标变量进行 8:2 分层抽样；仅在训练集上对连续特征等频分 5 箱，对分类特征保持原类别且不合并，不要求 WOE 单调，并以 \(IV>0.02\) 保留 17 个特征。随后采用 One-Hot 编码和类别权重建立逻辑回归与随机森林。逻辑回归 Recall 为 0.7237；随机森林 Precision、F1、最大 KS 和第一十分位 Lift 分别为 0.4994、0.5806、0.6665 和 4.5254，前 10% 客户认购率为 59.33%。结果表明，随机森林具有更好的名单排序与营销分层能力。

**关键词**：银行电话营销；WOE；IV；逻辑回归；随机森林；Lift；KS
