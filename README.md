# progress-bar
A Ring Progress Bar

##参数说明：
container: '进度条所在的容器元素的id名称',
value: '显示的百分比值',
valueColor: '百分比值的颜色'
color: '进度条颜色',
backColor: '进度条背景颜色',
radius: '圆环最外圆半径'

使用实例：
  
  import { CircularScrollBar } from 'CircularScrollBar';
  new CircularScrollBar({
    container: 'con',
    value: '100',
    valueColor: 'red',
    color: '#316ccb',
    backColor: '#ccc',
    radius: '200'
  }).init()