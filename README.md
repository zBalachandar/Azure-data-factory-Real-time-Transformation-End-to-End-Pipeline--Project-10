# Azure-data-factory-Real-time-Transformation-end-to-end-pipeline-Project
In this project we are going to do one end to end Realtime azure data factory project . we will see how we can setup azure data factory pipeline. how to transform data using adf data flow.

<div align="center">
  <a href="#">
    <img src="https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/531ef59f65fb8326a86e172d8802420763c92ad9/Assets/AZURE%20portal%20ov.png" alt="Banner" width="720">
  </a>

  <div id="user-content-toc">
    <ul>
      <summary><h1 style="display: inline-block;"> End to End Data-Pipeline-Project </h1></summary>
    </ul>
  </div>
  
  <p>Data Pipeline using Azure DataFactory</p>
</div>
<br>

### 💾 Dataset
Dataset link: https://docs.google.com/document/d/11qj5uqPNU2wEy6qRAZe30vVCimOoj_cAjabpmIMhRok/edit

### Business Requirement.
![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/531ef59f65fb8326a86e172d8802420763c92ad9/Assets/business%20req.jpg)

### Design and Development of pipeline:
![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/531ef59f65fb8326a86e172d8802420763c92ad9/Assets/sink%20config%20in%20ADF.png)


### Project steps to follow: 
what we have covered in this project:

- We have Covered End to End ADF Pipeline Project 
- Developed the Data Pipeline according to the business requirement


<a name="data-transformation"></a>
### ⚙️ Data Pipeline
 Create the resources for Data pipeline and processing using AZURE DATA FACTORY.
![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/531ef59f65fb8326a86e172d8802420763c92ad9/Assets/AZURE%20portal%20ov.png)

Azure Blob Storage -input Container:
![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/93b868a93a4f407a27143a8797420ce942ebc83d/Assets/AZURE%20Datalake%20storage%20containers.png)

![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/531ef59f65fb8326a86e172d8802420763c92ad9/Assets/Input%20sales%20data%20file.png)

Create the Azure Data Factory:
![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/531ef59f65fb8326a86e172d8802420763c92ad9/Assets/Datafactory%20ov.png)

Create the Copy Activity :
![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/531ef59f65fb8326a86e172d8802420763c92ad9/Assets/Datafactory%20ov.png)

Create Source point: 
![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/93b868a93a4f407a27143a8797420ce942ebc83d/Assets/dataflow%20source.png)

![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/93b868a93a4f407a27143a8797420ce942ebc83d/Assets/pivot%20transformation%20in%20ADF.png)

Sink :
![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/93b868a93a4f407a27143a8797420ce942ebc83d/Assets/sink%20config%20in%20ADF.png)

 Debug:
![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/93b868a93a4f407a27143a8797420ce942ebc83d/Assets/Dataflow%20debug.png)

Data Preview:
![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/93b868a93a4f407a27143a8797420ce942ebc83d/Assets/Sales%20data%20preview%20in%20adf.png)

pipeline triggered manually:
![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/93b868a93a4f407a27143a8797420ce942ebc83d/Assets/pipeline%20triggered.png)

Results of pipeline:
![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/93b868a93a4f407a27143a8797420ce942ebc83d/Assets/Success%20results%20in%20ADF%20preview%20data.png)

Publish all the Activities and dataflow:
![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/93b868a93a4f407a27143a8797420ce942ebc83d/Assets/pipeline%20publish.png)

Triggered the dataset pipeline:
![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/93b868a93a4f407a27143a8797420ce942ebc83d/Assets/pipeline%20triggered.png)

Pipeline Trigger in progress status:
![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/93b868a93a4f407a27143a8797420ce942ebc83d/Assets/pipeline%20triggered%20inn%20progess.png)

Pipeline Trigger status Success:
![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/93b868a93a4f407a27143a8797420ce942ebc83d/Assets/pipeline%20ran%20success.png)

Container in Output files
![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/93b868a93a4f407a27143a8797420ce942ebc83d/Assets/output%20file%20succeed.png)

Desired Output :
![image](https://github.com/zBalachandar/Azure-data-factory-Real-time-Transformation-end-to-end-Pipeline-Project-10/blob/93b868a93a4f407a27143a8797420ce942ebc83d/Assets/output%20file%20edit%20view..Desired%20results%20end.png)





### 🛠️ Technologies Used

- **Data Pipeline**: Azure Data Factory
- **Data processing(pivot)**: ADF

<a name="credits"></a>
## 📋 Credits

- This Project is inspired by the video of the [YouTube Channel "Learn by doing it"](https://www.youtube.com/watch?v=pMqnvXgPKlI&list=PLOlK8ytA0MghGmAAT8W2u7VYmICdzeU5t&index=1&t=96s)  

<a name="contact"></a>
## 📨 Contact Me

[LinkedIn](https://www.linkedin.com/in/balachandars2022/) •
[Gmail](balachandar2014elu@gmail.com)  •

