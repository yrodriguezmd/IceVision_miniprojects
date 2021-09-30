### IceVision_miniprojects
Computer vision mini-projects using Airctic/ IceVision

#### 01_object_detection_start

Focus:  Starting with IceVision, pets dataset, mmdet, retinanet/resnet, bboxes, COCOmetric (mAP)

Published:  Medium, August 2021.

https://medium.com/@yrodriguezmd/object-detection-using-a-deep-neural-network-213ec8ac2da8


#### 02_Object Detection fasterrcnn, yolo5, retinanet, effdet 2021_8_23

Focus:  Object detection using faster rcnn, yolo5, retinanet, efficientdet; class label adjustment

Published: Medium, August 2021,

https://medium.com/@yrodriguezmd/different-models-for-object-detection-9c5cda7863c1

#### 03_testing_fine_tune

Finding:  Fine_tune has a cumulative effect, LR gets smaller on subsequent iterations

#### 04_VOC 

Focus: Using IceVision voc dataset and parser, modelling with faster rcnn, yolov5, retinanet and efficientdet

#### 05_Plantdoc local upload, csv, custom parser

Focus:  Using plantsdoc tensorflow OD csv from roboflow, local computer download and upload, making a custom parser

Published: Medium, 2021, September

https://medium.com/@yrodriguezmd/the-custom-parser-a-key-to-a-good-data-harvest-10e24d0d8a71

#### 06_Plantdoc git, csv, custom parser

Focus:  Using git clone, with separate csv and images, making a custom parser

Mentioned in:  https://medium.com/@yrodriguezmd/the-custom-parser-a-key-to-a-good-data-harvest-10e24d0d8a71

#### 07_Plantdoc for notebook

Focus: Revision of airctic/icedata/notebooks/dev/plantdoc.ipynb to update codes, tutorial

Publication:  submitted for open-source PR, 2021 September

https://github.com/airctic/icedata/tree/master/notebooks/dev

#### 08_Plantdoc git, custom parser, model

Focus: Using plantdoc, uploaded via git clone, custom parser and modelling using faster rcnn, yolov5, retinanet and efficientdet

Publication:  Medium, 2021 September

https://medium.com/@yrodriguezmd/modelling-for-leaf-disease-detection-e16554a14bee

#### 09_BCCD new

Focus: Using a revised BCCD dataset (better annotation), upload via git clone, voc parser, no explicit class_map, modelling (final with yolov5), callbacks, save.  (Fit_one_cycle not included-> placed in IV_in_the_works) 

Publication:  Medium, 2021 September

https://medium.com/@yrodriguezmd/a-close-look-on-modelling-blood-cells-4625e832311f

#### 10_BCCD_Dataset for Notebook

Focus: BCCD Dataset for VOCBBoxParsing and modelling.  Based on IV BCCD new.  

Publication: submitted for open-source PR, 2021 September as airctic/icedata/notebooks/dev/bccd_rev

https://github.com/airctic/icedata/pulls

Branch path: notebooks/dev/bccd_dev.ipynb

#### 11 and 12_wheat Kaggle_source and _yolov5

Focus: Global wheat dataset, custom parsing and modelling (with extension via fit_one_cycle).

IV_wheat_kaggle_works!! shows custom parsing using 'source' as class.  Final model using Faster R-CNN.

IV_wheat_kaggle_yolov5 shows custom parsing with single class 'wheat'.  Final model using YOLOv5, mAP 0.46 after 40 epochs (still with room to increase,
but should be adequate for wheat head detection purposes).

Publication: Medium, September 2021.

https://medium.com/@yrodriguezmd/artificial-intelligence-can-help-feed-humans-9233f1c941f6

#### 13_custom_parser

Focus:  Simple custom Parser for a single-object type detection, based on wheat dataset.

Publication: submitted for open-source PR, 2021 September as airctic/icedata/notebooks/custom_parser

https://github.com/airctic/icedata/pull/121

#### 14_pseudolabel_pilot15

Focus:  Using a pretrained Retinanet model for inference of bboxes and object_ids, creating a coco json file, refining the annotations in roboflow and parsing the resulting image and annotations.

Publication: pending


