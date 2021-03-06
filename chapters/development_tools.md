# Development Tools

The Vulkan ecosystem consists of many tools for development. This is **not** a full list and this is offered as a good starting point for many developers. Please continue to do your own research and search for other tools as the development ecosystem is much larger than what can reasonably fit on a single Markdown page.

Khronos hosts [Vulkan Samples](https://github.com/KhronosGroup/Vulkan-Samples), a collection of code and tutorials that demonstrates API usage and explains the implementation of performance best practices.

## Khronos Validation Layer

The [Khronos Validation Layers](./validation_overview.md#khronos-validation-layer) is every developer's first layer of defense when debugging their Vulkan application and this is the reason it is at the top of this list. Read the [Validation Overview chapter](./validation_overview.md) for more details.

## Vulkan Layers

Besides the Validation Layers, there are also other publicly available layers that can be used to help in development.

- [API Logging](https://vulkan.lunarg.com/doc/sdk/latest/windows/api_dump_layer.html) - Vulkan SDK layer for logging API calls.
- [Arm PerfDoc layer](https://github.com/ARM-software/perfdoc) - Checks Vulkan applications for best practices on Arm Mali devices.
- [LunarG Best Practices layer](https://vulkan.lunarg.com/doc/sdk/latest/windows/best_practices.html) - Highlights potential performance issues, questionable usage patterns, common mistakes.
- [Simulate device properties](https://vulkan.lunarg.com/doc/sdk/latest/windows/device_simulation_layer.html) - Vulkan SDK layer for testing device properties on any device.
- [Capture and Replay](https://vulkan.lunarg.com/doc/sdk/latest/windows/capture_tools.html) - GFXReconstruct software for capturing and replaying Vulkan API calls. Note: this link takes you to the desktop version of the documentation. Full Android support is also available at <https://github.com/LunarG/gfxreconstruct>
- [Take screenshots](https://vulkan.lunarg.com/doc/sdk/latest/windows/screenshot_layer.html) - Captures the rendered image to a viewable image.
- [Track FPS](https://vulkan.lunarg.com/doc/sdk/latest/windows/monitor_layer.html) - Logs FPS information.

## Debugging

Debugging something running on a GPU can be incredibly hard, luckily there are tools out there to help.

- [Arm Graphics Analyzer](https://developer.arm.com/tools-and-software/graphics-and-gaming/arm-mobile-studio/components/graphics-analyzer)
- [GAPID](https://github.com/google/gapid)
- [NVIDIA Nsight](https://developer.nvidia.com/nsight-graphics)
- [PVRCarbon](https://www.imgtec.com/developers/)
- [RenderDoc](https://renderdoc.org/)

## Profiling

With anything related to a GPU it is best to not assume and profile when possible. Here is a list of known profilers to aid in your development.

- [AMD Radeon GPU Profiler](https://gpuopen.com/rgp/) - Low-level performance analysis tool for AMD Radeon GPUs.
- [Arm Streamline Performance Analyzer](https://developer.arm.com/tools-and-software/graphics-and-gaming/arm-mobile-studio/components/streamline-performance-analyzer) - Visualize the performance of mobile games and applications for a broad range of devices, using Arm Mobile Studio.
- [Intel(R) GPA](https://software.intel.com/content/www/us/en/develop/tools/graphics-performance-analyzers.html) - Intel's Graphics Performance Analyzers that supports capturing and analyzing multi-frame streams of Vulkan apps.
- [OCAT](https://github.com/GPUOpen-Tools/OCAT) - The Open Capture and Analytics Tool (OCAT) provides an FPS overlay and performance measurement for D3D11, D3D12, and Vulkan.
- [PVRTune](https://www.imgtec.com/developers/)
- [Qualcomm Snapdragon Profiler](https://developer.qualcomm.com/software/snapdragon-profiler) - Profiling tool targeting Adreno GPU.
