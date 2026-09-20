<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="e-amrnb6r"/><rect class="on4ow-bik"/><path class="ivt-xdbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:euro-news" /></template>
<style>
.e-amrnb6r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.987 25.607l-1.965 6.309l-1.964-6.309l-1.964 6.309l-1.964-6.309m10.304 5.777c.434.365.904.532 1.958.532h.534c.87 0 1.574-.706 1.574-1.577s-.705-1.577-1.574-1.577h-1.068c-.87 0-1.574-.707-1.574-1.578c0-.87.704-1.577 1.574-1.577h.534c1.054 0 1.523.167 1.958.532m-24.088 5.778v-3.929a2.38 2.38 0 0 0-4.762 0m0 3.928v-6.309m11.995 5.108a2.38 2.38 0 0 1-4.45-1.18v-1.547a2.38 2.38 0 0 1 4.762 0v.774h-4.761");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.ivt-xdbef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.913 16.084v3.928a2.38 2.38 0 0 0 4.762 0v-3.928m-.001 3.928v2.381m2.616-3.929a2.38 2.38 0 0 1 2.38-2.38m-2.38 0v6.309m-10.34-1.202a2.38 2.38 0 0 1-4.45-1.18v-1.547a2.38 2.38 0 0 1 4.762 0v.774H9.5");
}

.on4ow-bik {
  width: 4.762px;
  height: 6.309px;
  x: 28.594px;
  y: 16.084px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.381px;
  ry: 2.381px;
}

</style>
