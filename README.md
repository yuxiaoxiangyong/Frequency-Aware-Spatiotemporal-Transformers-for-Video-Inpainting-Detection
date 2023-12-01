# FAST
This is an unofficial implementation of [Frequency-Aware-Spatiotemporal-Transformers-for-Video-Inpainting-Detection(ICCV 2021).](https://openaccess.thecvf.com/content/ICCV2021/papers/Yu_Frequency-Aware_Spatiotemporal_Transformers_for_Video_Inpainting_Detection_ICCV_2021_paper.pdf)

## <a name="dataset"></a>Dataset Descriptions.
- In the paper, the author use davis2016 dataset inpainted by [VI](https://github.com/mcahny/Deep-Video-Inpainting)  [OP](https://github.com/seoungwugoh/opn-demo)  [CP](https://github.com/shleecs/Copy-and-Paste-Networks-for-Deep-Video-Inpainting) to make the Intra-Dataset and Cross-Method Evaluation.
- At the same time, the [FVI Dataset](http://arxiv.org/abs/1904.10247) is selected to excute the Cross-Dataset&Method evaluation.

## <a name="reproduction_tables"></a>Reproduction Results of FAST.
  | Methods  | VI*        |  OP*      |  CP        | 
  | :------: | :---:      | :----:    |:---:       | 
  | Papers   | 0.61/0.73  | 0.65/0.78 | 0.63/0.76  | 
  | Ours     | 0.62/0.74  | 0.70/0.81 | 0.61/0.74  |

  | Methods  | VI*        |  OP       |  CP*       |
  | :------: | :---:      | :----:    |:---:       | 
  | Papers   | 0.57/0.68  | 0.22/0.34 | 0.76/0.83  |
  | Ours     | 0.65/0.76  | 0.43/0.56 | 0.72/0.82  |

  | Methods  |    VI      |  OP*      |  CP*       |
  | :------: | :---:      | :----:    |:---:       |
  | Papers   | 0.32/0.49  | 0.78/0.87 | 0.82/0.90  |
  | Ours     | *  | * | *  |
## <a name="reproduction_tables"></a>Reproduction Results of VIDNet.
  | Methods  | VI*        |  OP*      |  CP        | 
  | :------: | :---:      | :----:    |:---:       | 
  | VIDNet(IN)   | 0.59/0.70  | 0.59/0.71 | 0.57/0.69  | 
  | Ours     | 0.59/0.71  | 0.67/0.77 | 0.53/0.66  |

  | Methods  | VI*        |  OP       |  CP*       |
  | :------: | :---:      | :----:    |:---:       | 
  | VIDNet   | 0.61/0.73  | 0.65/0.78 | 0.63/0.76  |
  | Ours     | *  | * | *  |

  | Methods  |    VI      |  OP*      |  CP*       |
  | :------: | :---:      | :----:    |:---:       |
  | VIDNet   | 0.61/0.73  | 0.65/0.78 | 0.63/0.76  |
  | Ours     | *  | * | *  |
