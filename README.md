# CBIR
Large-scale image retrival by deep learning(基于深度学习的大规模图像检索)
=========================================================================

How to the use this project files

* step-1
Finetune the model base on your image data

* step-2
compute_fea_for_cbir.py
Compute the image feature by the finetuned model, and save the to pkl files

* step-3
dump_data_to_pkl.py
Collect the feature pkl files to dic format: id_fc7_fc8

* step-4
dump_lsh_to_pkl.py
Dump the fc8 features by lsh

* step-5
app_cbir.py
Upload a imagefile and search the similar images


Cite the paper:

Deep Learning of Binary Hash Codes for Fast Image Retrieval
K. Lin, H.-F. Yang, J.-H. Hsiao, C.-S. Chen
CVPR Workshop (CVPRW) on Deep Learning in Computer Vision, DeepVision 2015, June 2015.

![image](https://github.com/zhaotaomcp/CBIR/blob/master/screenshots/Image_retrieval.png)
