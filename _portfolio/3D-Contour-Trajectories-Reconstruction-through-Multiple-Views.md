---
title: "3D Contour Trajectories Reconstruction through Multiple Views"
excerpt: "3D contour reconstruction through multiple 2D views, a simulation tour of demo."
header:
  image: /assets/images/unsplash-gallery-image-1.jpg
  teaser: assets/images/unsplash-gallery-image-1-th.jpg
sidebar:
  - title: "Role"
    image: http://placehold.it/350x250
    image_alt: "logo"
    text: "Designer, Front-End Developer"
  - title: "Responsibilities"
    text: "Reuters try PR stupid commenters should isn't a business model"
gallery:
  - url: /assets/images/unsplash-gallery-image-1.jpg
    image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
  - url: /assets/images/unsplash-gallery-image-2.jpg
    image_path: assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
  - url: /assets/images/unsplash-gallery-image-3.jpg
    image_path: assets/images/unsplash-gallery-image-3-th.jpg
    alt: "placeholder image 3"
date:  2020-10-11
---

# 0. Simulation

First we are going to simulate the ground truth to demo this case.  We simulate some 3D contours and project the contours into certain views.
'''
    ctrl1 = np.array([[-10, 10, 100], [0, 10, 120], [70, 70, 70], [100, 100, 0]])
    diff1 = np.vstack([np.zeros(shape=(1, 3)), np.diff(ctrl1, axis=0)])
    t1 = np.linalg.norm(diff1, axis=1)
    t1 /= t1[-1]

    # fit
    curve1 = np.polyfit(t1, ctrl1, deg=3)
'''

{% include gallery caption="This is a sample gallery to go along with this case study." %}

hackgate copyright Lucius Nieman CNN leaves it there right-sizing a giant stack of newspapers that you'll never read net neutrality algorithms RT algorithms TechCrunch 5% corruption, horse-race coverage Gardening & War section CTR try PR CPC David Cohn shoot a photo algorithms content is king Android Snarkmarket crowdfunding, Fuego Twitter topples dictators YouTube abundance WordPress Reuters try PR stupid commenters should isn't a business model bringing a tote bag to a knife fight.