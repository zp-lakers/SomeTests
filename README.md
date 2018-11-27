# SomeTests
for some problems

1.eclipse新建一个项目，在项目src文件夹下new一个folder放图片，结果发现folder显示package的视图。
解决办法：
  右键项目名称——>properties——>Java Build Path——>Source——>选择Exclude:(None)——>Edit——>Exclusion 办法patterns:一项右侧——>Add——>Browse...——>变成   包的文件夹（我这里是Image）Image——>OK——>OK——>Finish（这个不能省）

