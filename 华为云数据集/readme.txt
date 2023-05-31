文件介绍：
resized_data：
缩放至256*256的图片，共14w+张。

enhanced_data：
对resized_data中的每张图片进行增强后的图片，增强操作包括旋转、亮度、对比度、饱和度、色度。
增强程度随机、操作顺序随机，具体见代码文件。

label：
其中每个txt文件对应同名图片的标签信息

garbage_classify_rule.json：
标签对应的具体垃圾类别名称

数据增强.ipynb：
代码文件，如果要运行请注意路径。