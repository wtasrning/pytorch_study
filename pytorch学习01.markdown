目前目标检测所需要的图片数据来源主要为https://cocodataset.org


一·目标检测的性能指标
除了常用的混淆矩阵，还经常使用IoU(Intersection over Union)来衡量，
IoU=Area of Overlap/Area of Union.即预测范围与实际范围的交集/预测范围与实际范围的并集
当IoU>=0.5时，视作TP；IoU<0.5时，视作FP；物体存在却没有被检测出来；为FN



AP(Average Precision)是衡量学习出来的模型在每个类别上的好坏，map衡量的是在所有类别上的好坏。

