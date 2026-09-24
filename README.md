# NaviGS

> 🚧 **Coming Soon**
>
> The **NaviGS** dataset will be publicly released soon.

NaviGS is a real-world 3D Gaussian Splatting (3DGS) dataset comprising **120 high-fidelity indoor and outdoor scenes**, covering **over 50,000 m²** across **10 diverse scene categories**. The dataset provides RGB images, depth observations, camera poses, 3D Gaussian Splatting (3DGS) representations, reconstructed meshes, and hierarchical scene graphs.


## Dataset Structure

```text
NaviGS/
├── RGB_scene/
│   ├── scene_0/
│   │   ├── RGB/
│   │   ├── depth/
│   │   ├── pose/
│   │   ├── 3dgs/
│   │   └── mesh/
│   ├── scene_1/
│   ├── scene_2/
│   ├── scene_3/
│   └── scene_4/
│
└── semantic_scene/
    ├── apartroom1/
    │   ├── RGB/
    │   ├── depth/
    │   ├── pose/
    │   ├── 3dgs/
    │   ├── mesh/
    │   └── scenegraph/
    ├── apartroom2/
    ├── apartroom3/
    ├── resthome1/
    └── meetingroom1/
```

## Data Organization

### RGB Scenes

The `RGB_scene` directory contains five scenes. Each scene includes:

* `RGB/` — RGB images
* `depth/` — Depth observations
* `pose/` — Camera poses and trajectories
* `3dgs/` — 3D Gaussian Splatting representations
* `mesh/` — Reconstructed meshes


### Semantic Scenes

The `semantic_scene` directory contains five scenes with semantic and hierarchical scene understanding annotations.

Each semantic scene includes:

* `RGB/` — RGB images
* `depth/` — Depth observations
* `pose/` — Camera poses and trajectories
* `3dgs/` — 3D Gaussian Splatting representations
* `mesh/` — Reconstructed meshes
* `scenegraph/` — Hierarchical 3D scene graphs

The scene graphs follow the hierarchical **floor–room–stuff–object** organization and provide semantic and spatial relationships between scene elements.

## Scenes

### RGB Scenes

* `scene_0`
* `scene_1`
* `scene_2`
* `scene_3`
* `scene_4`

### Semantic Scenes

* `apartroom1`
* `apartroom2`
* `apartroom3`
* `resthome1`
* `meetingroom1`

## Release

The dataset will be publicly available soon.

More details, download links, documentation, and usage instructions will be provided upon release.
