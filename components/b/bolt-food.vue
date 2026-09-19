<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iri6kjvdk"/><path class="r_2elib3w"/><path class="e4-jxfyoz"/><circle class="sq8ei-b_c"/><rect class="jh4g4vb4l"/><rect class="j6h3h3mup"/><path class="fi3x_zayc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bolt-food" /></template>
<style>
.e4-jxfyoz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 16.138h4.929a2.95 2.95 0 0 1 2.957 2.94v.017h0a2.95 2.95 0 0 1-2.941 2.957h-4.946m12.733 0a2.95 2.95 0 0 1-2.957-2.94v-1.824a2.95 2.95 0 0 1 2.94-2.957h.017a2.95 2.95 0 0 1 2.957 2.94v1.824a2.95 2.95 0 0 1-2.94 2.957zm8.215-10.185v8.707a1.47 1.47 0 0 0 1.462 1.478h.591m-5.421-10.185v10.185m1.807-7.721h1.561m0 0h1.56");
}

.fi3x_zayc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.361 31.862h3.844m-3.844 5.914V25.948h5.914m21.365 6.949a2.957 2.957 0 0 0-2.958-2.957h0a2.957 2.957 0 0 0-2.957 2.957v1.922a2.957 2.957 0 0 0 2.957 2.957h0a2.957 2.957 0 0 0 2.957-2.957m0 2.957V25.948");
}

.iri6kjvdk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-26 16.552V10.224");
}

.j6h3h3mup {
  width: 5.914px;
  height: 7.836px;
  x: 23.915px;
  y: 29.94px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.957px;
  ry: 2.957px;
}

.jh4g4vb4l {
  width: 5.914px;
  height: 7.836px;
  x: 16.023px;
  y: 29.94px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.957px;
  ry: 2.957px;
}

.r_2elib3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 10.224h4.929a2.95 2.95 0 0 1 2.957 2.94v.017h0a2.95 2.95 0 0 1-2.941 2.957h-4.946");
}

.sq8ei-b_c {
  cx: 25.232px;
  cy: 23.777px;
  r: 0.75px;
  fill: currentColor;
}

</style>
