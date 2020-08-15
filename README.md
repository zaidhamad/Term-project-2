# Term-project-2
All source codes are in the folder Sources/.

Two classes BinarySVM and MultiSVM are defined in the file svm.py.

demo_test.py, multi_test.py and svm_test.py all used to debug the SMO algorithm:

demo_test.py includes a data generator which generates 2-dimensional linear separable/almost-separable/circular data of 2 classes, then visualize the data points and train a BinarySVM.

Similarly, multi_test.py serves for testing MultiSVM.

In svm_test.py, some real data are extracted from the MNIST dataset and are visualized using the PCA technique.

Finally, svm_test_full.py trains a SVM classifier on the whole MNIST data.
