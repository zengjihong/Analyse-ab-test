# 【A/B测试】支付宝营销策略效果分析
A/Btest常用于比较不同的设计、运营方案的优劣，以辅助决策。本分析以支付宝营销活动为例，通过广告点击率指标比较两组营销策略的广告投放效果。
本文所用的数据集来源于阿里云天池：https://tianchi.aliyun.com/dataset/dataDetail?dataId=50893&lang=zh-cn

本分析报告的主要使用广告点击情况数据集(effect_tb.csv)，涉及字段如下：
- dmp_id：营销策略编号（源数据文档未作说明，这里根据数据情况设定为1：对照组，2：营销策略一，3：营销策略二）
- user_id：支付宝用户ID
- label：用户当天是否点击活动广告（0：未点击，1：点击）

代码主要分为以下几个部分：

#### 1.数据处理
##### 1.1 数据导入和清洗
- 导入数据
- 总览数据概况
- 判断数据重复值情况
- 判断数据缺失值情况
- 判断数据异常值情况
##### 1.2 样本容量检验
#### 2. 假设检验
##### 2.1 方法一：公式计算
##### 2.2 方法二：python函数计算
##### 2.3 方法三：蒙特卡洛法（模拟法）
#### 3.结论

