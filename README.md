# Pytorch

- Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. N., ... & Polosukhin, I. (2017). Attention is all you need. In Advances in neural information processing systems (pp. 5998-6008).

- Mullenbach, J., Wiegreffe, S., Duke, J., Sun, J., & Eisenstein, J. (2018). Explainable prediction of medical codes from clinical text. arXiv preprint arXiv:1802.05695.

- Kim, Y. (2014). Convolutional neural networks for sentence classification. arXiv preprint arXiv:1408.5882.


| Field        |  Type  | Description                               |
| -------------| ------ | ----------------------------------------- |
| mode         | str | REQUIRED ; inference mode ( "single", "batch" )  |
| batch_size   | int | OPTIONAL ; If mode =  "batch", the model will inference with batch. Default batch size is 128|
| text         | str/list | REQUIRED ; Input content (unit content). If mode =  "single", text should be string; If mode =  "batch", text should be list of string|
