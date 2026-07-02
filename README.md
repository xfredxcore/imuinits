![Interface Screenshot](screenshot.png)

# imuinits

A fast, lightweight, and flexible multi-step unit converter built with **Dear ImGui**, **GLFW**, and **OpenGL3**, powered by the robust **GNU Units** engine under the hood.

## Features
* **Multi-step Calculations:** Evaluate complex formulas like `10 meter / 2 meter * 30 footballfield`.
* **Dynamic Autocomplete:** Predictive input hints that instantly parse and match your text against the GNU Units database on the fly.
* **Zero External Dependencies for Fonts:** Uses the highly optimized, built-in ImGui default font system.
* **Modern Dark Theme:** Clean, scannable UI designed for engineers.

## Requirements
* `units`
* `glfw`
* `opengl`
* `g++` compiler

## Installation & Compilation
Clone the repository and compile using the following command:

```bash
g++ main.cpp imgui.cpp imgui_draw.cpp imgui_tables.cpp imgui_widgets.cpp imgui_impl_glfw.cpp imgui_impl_opengl3.cpp -lglfw -lGL -o imuinits
