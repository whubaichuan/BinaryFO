# BinaryFO: Binary Forward-Only Algorithms

This repository provides the reproducible code for all the reported results in the paper **BinaryFO: Binary Forward-Only Algorithms**.


The codes for binary version of the state-of-the-art forward-only algorithms are provided, including Binary-PEPITA<sup>[2]</sup>, Binary-FF<sup>[3]</sup> and Binary-BP on MNIST, CIFAR-10, [MIT-MIT](https://www.physionet.org/content/mitdb/1.0.0/) datastes. 


The codes are shown as follows:
- Binary-BP: ``python BinaryBP/Main.py ``
- Binary-PEPITA: ``python BinaryPEPITA/pepita.py ``
- Binary-FF: ``python BinaryFF/main.py ``

> The parameters `dataset`, `binary_w` (binary weights) and `binary_a` (binary activations) need to be changed accordingly.


## References


[1] Dellaferrera, Giorgia, and Gabriel Kreiman. "Error-driven input modulation: solving the credit assignment problem without a backward pass." International Conference on Machine Learning. PMLR, 2022.

[2] Hinton, Geoffrey. "The forward-forward algorithm: Some preliminary investigations." arXiv preprint arXiv:2212.13345 (2022).

