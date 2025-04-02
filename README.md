# avatar-move-into-effect

原理：
1. 本质上就是三个盒子hover改变其中一个让图片正常展示出来
2. 其从中心变大小的盒子使用的是clip-path，绘制圆。
3. 然后加个hover和transition过度效果即可实现。
