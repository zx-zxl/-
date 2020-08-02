# -
2020年新工科联盟-Xilinx暑期学校（Summer School）项目。
项目概要：采集开发平台通过FPG上自带的imu传感器的数据，随后对数据进行滤波，利用滤波后的数据计算得出一分钟开发板被摇动的次数。将次数数据发送给ESP32最后由ESP32上传到服务器进行显示。学习到FPGA和ESP32的开发，以及协同工作的原理，板载FPGA读取陀螺仪的数据，以及通过ESP32实现PC端和AWS的连接。
使用的工具：vivado2018.3    flash_download_tools_v3.6.7    arduino IDE  uPyCraft
板卡型号：xc7s15ftgb196-1
images:照片存放
Sourcecode：
存放项⽬源代码。FPGA源码，ESP32源码或者其它相关部件的源码应该单独建立文件夹存放。
ExecutableFiles：
本⽬录存放可直接下载到板卡使⽤的FPGA 比特流文件，ESP32的可执⾏文件或者其它部件上可直
接运⾏的可执⾏文件。
