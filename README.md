# cnn
My frist cnn program, it can use picture to train and save the cnn model, by Sun Yi, base on tensorflow and opencv. 

you can use this program by:

python CNN_train.py

python CNN_test.py

--------file list-------

CNN.conf               : This is a config file, you can use it to control all things in train and test processing.

CNN_structure.py       : The CNN structure in this file.

CNN_train.py           : Use pictures to train and save CNN model, please put your pictures in directory /data, like flower_photos.

CNN_test.py            : Use CNN model to divide pictures to directory /data.

image_preprocessing.py : Conversion from pictures to array.
