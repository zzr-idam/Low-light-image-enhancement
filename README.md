# Low-light-image-enhancement
Low-light image enhancement is a classical computer vision problem aiming to recover normal-exposure images from low-light images. However, convolutional neural networks commonly used in this field are good at sampling low-frequency local structural features in the spatial domain, which leads to unclear texture details of the reconstructed images. To alleviate this problem, we propose a novel module using the Fourier coefficients, which can recover high-quality texture details under the constraint of semantics in the frequency phase and supplement the spatial domain. In addition, we design a simple and efficient module for the image spatial domain using dilated convolutions with different receptive fields to alleviate the loss of detail caused by frequent downsampling. We integrate the above parts into an end-to-end dual branch network and design a novel loss committee and an adaptive fusion module to guide the network to flexibly combine spatial and frequency domain features to generate more pleasing visual effects. Finally, we evaluate the proposed network on public benchmarks. Extensive experimental results show that our method outperforms many existing state-of-the-art ones, showing outstanding performance and potential.

# Linke 

https://arxiv.org/abs/2209.07937

# Code

https://github.com/Zhuangyunliang/DPFNet
