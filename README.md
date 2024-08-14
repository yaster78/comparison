# SCube NeurIPS Rebuttal

## Qualitative Comparison with MVSplat & MVSGaussian

### Novel View Synthesis

<img src="assets/rebuttal_comp_1_crop-1.png" alt="" style="width: 100%;" />

<img src="assets/rebuttal_comp_3_crop-1.png" alt="" style="width: 100%;" />

### Visualization of 3D

Both MVSplat and MVSGaussian fail to model the true 3D geometry and the occluded parts of the scene and hence have unsatisfactory generalization capability to large-scale outdoor scenes.
Specifically, the geometry of MVSplat degenerates to a image plane, and the geometry of MVSGaussian contains too many outliers on the rays of the corresponding pixels.

<img src="assets/3D_comp_crop.jpg" alt="" style="width: 100%;" />
