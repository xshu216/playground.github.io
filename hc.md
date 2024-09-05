# hc

https://chatgpt.com/share/4b0ec090-8a9d-41dc-9b09-a702bfdde5a0



## 1. 识别
  https://blog.csdn.net/fQLGhfydG/article/details/137742234
  https://www.cjwk.cn/journal/guidelinesDetails/1711656969768937767
https://blog.csdn.net/wujianing_110117/article/details/104792076
https://zgglxb.chd.edu.cn/CN/lexeme/showArticleByLexeme.do?articleID=485
https://patents.google.com/patent/CN111114551B/zh
https://blog.csdn.net/NEON7788/article/details/139626477
https://m.fx361.cc/news/2019/0814/17619886.html
https://qikan.cqvip.com/Qikan/Article/Detail?id=669485370&from=Qikan_Article_Detail
https://bbs.elecfans.com/jishu_943568_1_1.html
https://blog.csdn.net/NRhpTJeu/article/details/135754976
https://pdf.dfcfw.com/pdf/H3_AP202307161592322615_1.pdf?1689584330000.pdf
基于贝叶斯模型的驾驶行为识别与预测
infocomm-journal.com
http://www.infocomm-journal.com › txxb › article
作者：王新胜 · 2018 · 被引用次数：1 — ... IMU收集的数据分割成不重叠的线性分段；然后，将线性分段和相机图像片段 ... 同时考虑了道路坡度对驾驶数据的影响，避免因为路况而影响结果的
https://cloud.tencent.com/developer/article/1746241
## 2. 方法
<img width="927" alt="image 4" src="https://github.com/user-attachments/assets/3a7d592c-5c49-4e4d-aa3e-4a8909824e78">
<img width="264" alt="image" src="https://github.com/user-attachments/assets/560e36b4-1454-4648-a700-c909546c1c8d">
<img width="250" alt="image 2" src="https://github.com/user-attachments/assets/4c995b71-d4d0-42dd-8a0a-bd03a60bb3d2">
<img width="522" alt="image 3" src="https://github.com/user-attachments/assets/6f7144f5-2520-4ce8-9801-df4bc11a81e0">


CN 110239554 B
使能，坡度大于阈值 （区分坡道防溜车，档位）
动态调整：油门开度信号+制动信号+方向盘转角信号+纵向加速度+换挡信号，适当延长坡度控制的更新时间
	适 当 延 长 坡 度 更 新 频 率 ，避 免 在 上 述 情 况 下 造 成 前 后 采 样 时 刻 坡 度 变化率过大，影响路面纵向坡度值获取的精确性的问题。




## 3. 融合

  ## 4. 补充知识点
  [can总线](https://community.infineon.com/t5/%E5%8D%9A%E5%AE%A2/%E6%B1%BD%E8%BD%A6CAN%E6%80%BB%E7%BA%BF%E8%AF%A6%E8%A7%A3/ba-p/572549#.)
  [can通讯理解](https://www.youtube.com/watch?v=sREP2e3jVYs)

##  Questions
CN 114312200 A
岚图汽车科技有限公司
一种车辆主动悬架的控制方法及装置
待优化：只考虑了车辆在特定坡道的条件下的通过能力，并没有考虑操稳性和舒适性
* 第一坡道距离：如果坡道角度大于接近角，则根据坡道角度、接近角及接近角对应的离地间隙计算第一坡道距离【T1】【T5】。
第二坡道距离：如果坡道角度大于离去角，则根据坡道角度、离去角及离去角对应的离地间隙计算第二坡道距离【T1】【T6】。
第三坡道距离：如果坡道角度大于纵向通过角，则根据坡道角度、纵向通过角及纵向通过角对应的离地间隙计算第三坡道距离【T1】【T5】。
筛选最大坡道距离：最后，从计算得到的第一坡道距离、第二坡道距离和第三坡道距离中筛选出最大坡道距离，并将该最大坡道距离作为坡道行驶高度
<img width="1178" alt="image" src="https://github.com/user-attachments/assets/b9c3d918-d772-423c-965b-45034a3b3da0">

  <img width="735" alt="image" src="https://github.com/user-attachments/assets/cd0a18ba-c6a9-4c6c-a33e-24cf42bf8efc">
接近角、离去角和纵向通过角与路面的纵向坡度是不同的概念，具体区别如下：

接近角（Approach Angle）：

接近角是指车辆前部在接近坡道或障碍物时，前轮与地面之间的夹角。它主要反映了车辆在前方障碍物或坡道的接近能力，影响车辆在上坡或越过障碍物时的安全性。
离去角（Departure Angle）：

离去角是指车辆后部在离开坡道或障碍物时，后轮与地面之间的夹角。它反映了车辆在后方障碍物或坡道的离去能力，影响车辆在下坡或越过障碍物时的安全性。
纵向通过角（Breakover Angle）：

纵向通过角是指车辆底盘中点与地面之间的夹角，主要用于评估车辆在通过高低起伏地形时的能力，尤其是在车辆的前后悬挂之间的高度变化。
路面的纵向坡度（Longitudinal Slope）：

路面的纵向坡度是指路面在某一段距离内的倾斜程度，通常用百分比或角度表示。它描述了路面相对于水平面的倾斜程度，影响车辆的行驶稳定性和动力需求。
主要区别：
性质：接近角、离去角和纵向通过角是车辆几何特性相关的角度，主要用于评估车辆在特定地形条件下的通过能力；而纵向坡度是路面特性，描述了路面的倾斜程度。
应用：接近角、离去角和纵向通过角用于判断车辆在特定坡道或障碍物条件下的适应性；纵向坡度则用于评估路面对车辆行驶的影响，如加速、制动和稳定性等。
<img width="682" alt="image" src="https://github.com/user-attachments/assets/db0f7191-da57-4f8d-a228-fc0686a588d8">

