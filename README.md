# Inter-Correlation
This repo contains the implementation of "Intra-Correlation Encoding for Chinese Sentence Intention Matching" in Keras & Tensorflow.

All codes you can find here:

%Google Drive: https://drive.google.com/drive/folders/1IFCwZEFyPGgO4z1Wwjlf35U3bivPk8NI?usp=sharing, or 

Baidu Netdisk: https://pan.baidu.com/s/1QstyW9AD3_ykyUuPb8V8Bw  password: vplk
# Usage for python code
## 0. Requirement
python 3.6  
numpy==1.16.4  
pandas==0.22.0  
tensorboard==1.12.0  
tensorflow-gpu==1.12.0  
keras==2.2.4  
gensim==3.0.0

## 1. Data preparation
The dataset is BQ & LCQMC.  
"The BQ Corpus: A Large-scale Domain-specific Chinese Corpus For Sentence Semantic Equivalence Identification", https://www.aclweb.org/anthology/D18-1536/.

"LCQMC: A Large-scale Chinese Question Matching Corpus", https://www.aclweb.org/anthology/C18-1166/.
## 2. Start the training process
python train.py  
## 3. Start the prediction process
python predict.py  
## 4. Load the trained model
You can download the codes and our trained model from here:

%Google Drive: https://drive.google.com/drive/folders/1IFCwZEFyPGgO4z1Wwjlf35U3bivPk8NI?usp=sharing, or 

Baidu Netdisk: https://pan.baidu.com/s/1QstyW9AD3_ykyUuPb8V8Bw  password: vplk, 

then run predict.py to get the experiment results in "Intra-Correlation Encoding for Chinese Sentence Intention Matching"
# Reference
If you find our source useful, please consider citing our work.

Xu Zhang, Yifeng Li, Wenpeng Lu, Ping Jian, Guoqiang Zhang. Intra-Correlation Encoding for Chinese Sentence Intention Matching[C]//Proceedings of the 28th International Conference on Computational Linguistics. 2020.
