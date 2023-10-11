# Author
Wendell T.

# YAnnot
Semi-Automatic Yolo Annotation Tool In Python

<table>
  <tr>
    <td>YAnnot</td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/38634222/175885482-baf10681-6ef5-45b5-873d-c4304e8fea73.png" width=640 height=480></td>
  </tr>
 </table>
 
## About the repository
* 'yolo_annotation_tool.py' : Main file to load images one-by-one from the dataset, and then annotate them.
* 'recognize_objects.py' : Object recognition class for pre-annotating images before manual annotation process.
* 'config.ini' : Edit data folder, output folder and label file path according to your preference. 

## Usage:
```
python yolo_annotation_tool.py
```
## Key buttons:
* 'S' : Save annotations
* 'L' : Change current class of labeling
* 'Esc' :  Exit the code

## Input images

<table>
  <tr>
    <td>Image 1</td>
     <td>Image 2</td>
     <td>Image 3</td>
  </tr>
  <tr>
    <td><img src="data/1.jpg" width=320 height=240></td>
    <td><img src="data/2.jpg" width=320 height=240></td>
    <td><img src="data/3.jpeg" width=320 height=240></td>
  </tr>
 </table>


## Output images (Pre-annotation)

<table>
  <tr>
    <td>Image 1</td>
     <td>Image 2</td>
     <td>Image 3</td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/38634222/175885476-e8b33fb0-f2be-4a4e-b1fc-ae493e03e85b.png" width=320 height=240></td>
    <td><img src="https://user-images.githubusercontent.com/38634222/175885461-93b0fafe-e135-4a76-9b6a-416de9a4513a.png" width=320 height=240></td>
    <td><img src="https://user-images.githubusercontent.com/38634222/175885482-baf10681-6ef5-45b5-873d-c4304e8fea73.png" width=320 height=240></td>
  </tr>
 </table>

