# OpenMMlabCamp_work3
OpenMMlabCamp-作业3
本次作业采用运用mmdet的rtmdet_tiny模型分别对balloon、drink简单数据集进行试验。


rtmdet_tiny针对balloon_dataset的试验：

配置文件见:[balloon_rtmdet.py](balloon_rtmdet/balloon_rtmdet)

训练日志见:[20230613_150737.log](balloon_rtmdet/20230613_150737.log)

验证集评估日志见:[20230613_152121.log](balloon_rtmdet/20230613_152121.log)

验证集评估指标：

![Snipaste_2023-06-13_15-22-30](https://github.com/wuwulin/OpenMMlabCamp_work3/assets/18210010/8b62b394-f2ea-4b63-8eaa-9159d47ee700)

预测图片：

![balloon_test](https://github.com/wuwulin/OpenMMlabCamp_work3/assets/18210010/8d0ced83-949f-426c-ae14-29f55219224f)

可视化分析：
![balloon_test_neck](https://github.com/wuwulin/OpenMMlabCamp_work3/assets/18210010/eda08709-b991-4940-ae84-cf1562557d55)
![balloon_test_m](https://github.com/wuwulin/OpenMMlabCamp_work3/assets/18210010/15064710-5a5b-47bd-8918-cf65d0f6f6f6)




rtmdet_tiny针对drink_dataset的试验：

配置文件见:[drink_rtmdet.py](drink_rtmdet/drink_rtmdet)

训练日志见:[20230613_103330.log](drink_rtmdet/20230613_103330.log)

验证集评估日志见:[20230613_111513.log](drink_rtmdet/20230613_111513.log)

验证集评估指标：

![Snipaste_2023-06-13_14-35-27](https://github.com/wuwulin/OpenMMlabCamp_work3/assets/18210010/7f1381d3-8ae2-4077-a616-0edf764f7e1e)

预测图片：

![wV0khm5FO2](https://github.com/wuwulin/OpenMMlabCamp_work3/assets/18210010/b9513ad9-6088-406c-8cd4-27e251556734)

可视化分析：
![wV0khm5FO2_bakbone](https://github.com/wuwulin/OpenMMlabCamp_work3/assets/18210010/c76013ad-6652-443e-936b-cbece75c5c28)


![wV0khm5FO2_grad](https://github.com/wuwulin/OpenMMlabCamp_work3/assets/18210010/f4cc94c8-811a-43f7-b53f-afddba652042)
