
STM32F407探索者开发板：无操作系统，已实现短信息识别并发送，获取定位信息，定位信息处理完成，具备GPS定位信息发送
STM32F407自制开发板：已经实现避障、蜂鸣器报警、震动马达功能    已完成GPS定位信息获取并处理 已解决运行几分钟后会死机的问题
20170803更新，自制板实现了短信的定制和取消功能

问题：									备注
1、运行一段时间会死机    				
										已解决；
										原因是：在获取不到定位信息时对数组长度进行运算，且对意外情况的数组长度运算


