# unicenter</br>
初始计划: arduino + 激光检测模块测试室内PM2.5</br>
then</br>
引入树莓派作为跳板，将数据搞到外网，做数据可视化</br>
then</br>
入坑 nrf24l01+作为点对点数据传输</br>
then</br>
可视化适用influxdb + grafana，既然搞了，为何不多加几个？</br>
then</br>
厨房增加CH-4 和CO的浓度报警，MQ-2,MQ-7</br>
then</br>
卧室增加温湿度检测 DS18B20，DHT22</br>
</br>
@2016.03.02,琢磨告警实现和移动端push的简易解决方案ing</br>
@2016.11.30,终于想起来把代码搞到github 上..</br>

------分割线--------</br>

目前进度： </br>

1.客厅有温度、湿度、pm2.5 以及pm10的传感器采集； </br>
2.厨房有CO 和CH4 的传感器采集； </br>
3.卧室有1 颗树莓派作为网关，将数据上传至AWS;  </br>
4.AWS 部署 influxdb + grafana 做数据存储和展示；  </br>


即将要做： </br>

1.增加 nrf24l01 一对多的实验，在家里增加更多的监控节点； </br>
2.逐步尝试探索低功耗的方法，将供电从常电切换至电池，灵活性赛高； </br>
3.增加告警机制（微信机器人已完成，欠server 端数据处理）； </br>
