# android-mascot-plaque

## Overview
This repository contains a CAD model featuring a customized, flat-profile design of the Android mascot. Built onto a square base plate, the design features the classic semicircular Android head, angled antennae, circular eyes, and stylized text, making it perfect for manufacturing as a physical plaque, sign. 

## How I Designed This
The design was modeled using a parametric CAD workflow, heavily relying on 2D sketching tools to build the distinct geometry before converting it into a 3D shape. Here is a breakdown of my design process:

### 1. Setting the Foundation
* **Base Plate:** I started by sketching a bounding rectangle on the primary plane to define the outer limits of the plaque. 

### 2. Drafting the Mascot Geometry
* **The Head:** I used a center-point arc anchored to the bottom edge of the rectangle. Sweeping this arc created the classic dome shape of the Android robot's head.
* **The Eyes:** Inside the dome, I sketched two center-point circles. These were constrained to be horizontally aligned and symmetrically spaced from the vertical center axis.
* **The Antennae:** I drew angled construction lines extending outward from the arc of the head. I then used an offset or slot tool to give these lines thickness, capping the ends with tangent arcs to create the rounded tips.

### 3. Adding Typography
* **Text Tool:** Along the top edge of the base plate, I utilized the sketch text tool to spell out "Android." 

### 4. Creating the 3D Profiles
* Once the 2D sketch was fully defined (as seen in `image_d07205.png`), I used extrusion tools on the distinct bounded regions. 
* By selecting the text, the head, the antennae, and the base plate separately, I was able to extrude them to different depths. This creates a multi-level relief effect, allowing the individual features to stand out from the background plate.

## Potential Applications
This model is highly versatile and can be exported for various manufacturing methods:
* **3D Printing:** Export as an `.STL` or `.3MF` file. The distinct extrusion levels make it perfect for multi-color 3D printing or manual filament swapping at specific layer heights.
* **Laser Engraving & CNC Routing:** The clear geometric boundaries and flat 2D profiles are ideal for importing as a `.DXF` to be CNC routed out of wood or laser-cut from acrylic.

## Files Included
* `image/Android-mascot-plaque.png`: The primary visual of the design.
* `exports/`: Directory for manufacturing files (such as `.STL`, `.STEP`, or `.DXF`).

## Usage
To replicate, manufacture, or modify this design:
1. Import the reference image or CAD files into your preferred CAD software.
2. Ensure the base plate thickness matches your stock material.
3. Apply distinct extrusions (cuts or additions) to the eyes, antennae, head, and text bodies as needed for your specific manufacturing hardware.
