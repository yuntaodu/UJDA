# Unsupervised domain adaptation with unified joint distribution alignment
This project implements our paper [unsupervised domain adaptation with unified joint distribution alignment](https://link.springer.com/chapter/10.1007/978-3-030-73197-7_30). Please refer to our paper [1] for the method and technical details.



## Prerequisites:
* Python3
* PyTorch ==0.4.1 (with suitable CUDA and CuDNN version)
* torchvision == 0.2.0
* Numpy
* tqdm

## Dataset:

You need to modify the path of the image in every ".txt" in "./data".

## Training:
run :

    python train.py --config ../config/dann.yml   --dataset Office-31   --src_address ../data/amazon.txt    --tgt_address     ../data/dslr.txt  --src_test_address ../data/amazon.txt



## Contact
If you have any problem about our code, feel free to contact 
- duyuntao@smail.nju.edu.cn
- yaoyueduzhen@outlook.com.

## Citation:
If you use this code for your research, please consider citing:

```
@inproceedings{Du2021UnsupervisedDA,
  title={Unsupervised Domain Adaptation with Unified Joint Distribution Alignment},
  author={Yuntao Du and Zhiwen Tan and Xiaowen Zhang and Yirong Yao and Hualei Yu and Chong-Jun Wang},
  booktitle={DASFAA},
  year={2021}
}
```
