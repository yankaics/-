# -
摘要：“打车难”问题是国民关注的热点问题之一。随着“互联网+”时代的到来，各种打车软件应运而生，并推出了多种出租车补贴方案，各种补贴方案是否能缓解打车难，仍有待研究。为此我们搜集相关数据，利用数学建模的方法，研究了“互联网+”时代的出租车资源配置问题，获得了一些有价值的结论。我们的主要工作如下： 由于题目未提供数据，通过查找资料，选择2011年同济大学数学建模夏令营D题提供的深圳市出租车GPS数据进行研究。因数据过于庞大且存在错误，故先要剔除空间、状态上不合理的数据，然后按照时间、经纬度、行驶状态进行归类整理。  问题一要求建立出租车资源供求匹配程度模型。我们选择出租车总量供需比 、出租车拥有量（万人） 、出租车空驶率 三项指标对深圳市出租车匹配程度进行研究。首先，基于出租车总量供需比研究出租车的供求匹配程度，通过查找资料得到出租车需求量的测定模型，代入数据得到2011年深圳市出租车需求量为26110辆，与实际出租车供给量15035辆作比，求得出租车总量供需比 为0.5758，表明2011年深圳市出租车总量的供需匹配程度较差。然后，基于出租车拥有量（万人）研究不同空间出租车的供求匹配程度，数据中深圳市各地区载客点数目比重可评估各地区出租车供给量，与该地区常住人口数（万人）求比值，得到深圳市不同空间出租车拥有量（万人），其中罗湖区、福田区和南山区的出租车拥有量大，出租车供求匹配程度高，而坪山新区和光明新区的出租车拥有量小，出租车供求匹配程度低。最后，基于出租车空驶率研究不同时间出租车资源的供求匹配程度。将一天分为24个时间单位，由数据得到各时间段的空驶时间和运营时间，两者相比得到各时间段的小时平均空驶率，其中在23:00—7:00出租车空驶率最高，出租车供求匹配程度较低，而在8:00—10:00和14:00—18:00空驶率较低，出租车供求匹配程度较高。 问题二通过建立补贴方案吸引力模型，对“缓解打车难”的帮助程度进行评估。我们认为吸引力越大，软件使用越广泛，对“缓解打车难”帮助越大。首先，以每笔补贴金额为指标，利用模糊数学中隶属函数建立补贴金额与吸引力隶属关系式，其中吸引力因子为6.414。结合各公司出租车补贴方案，求得当单笔补贴方案为10元和2元时吸引力分别为0.91220，0.0927。由于补贴方案随时间的推移，其吸引力会发生变化，构建修正模型，得到补贴方案的综合吸引力模型，求得在每笔补贴方案为10元和2元时其值分别为：6.4880,0.6595。 问题三要求设计打车软件补贴方案，并评价方案的合理性。其实质是构建评价补贴方案合理性模型。该模型主要由公司经营成本，顾客满意度和吸引力三因素决定。顾客满意度受到补贴金额影响，因为当补贴金额较高时，司机将会拒载沿边扬招乘客而使其满意度下降。利用非线性规划求解该模型，得到每笔补贴6.53元时结果最优。对于偏远地区、拥堵路段的打车难问题，本文通过建立司机满意度模型并与公司成本的实际相结合，得到对单个出租车的月补贴为860—1035元较合适。  关键词：供求匹配程度 补贴方案吸引力 满意度 “打车难”
