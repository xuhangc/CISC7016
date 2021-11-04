# CISC7016
## PPT 

[PPT](./ppt/NCA-GAN.pptx)

## Code

1. To train your own network, run `automata.py` first to train the differential cellular automata and autoencoder to generate good looking MNIST digits. 
2. Then using the generated model, run `automata_persistent_mnist.py` to train the automata to generate persistent digits. 
3. Finally using the new generated model, run `gan_mnist.py` to train a Generative Adversarial Network on the latent vectors of the autoencoder. 
4. Finally using that model and the model from `automata_persistent_mnist.py`, you can run `automata_test.py`. 
