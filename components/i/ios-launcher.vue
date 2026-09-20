<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><circle class="t1exc0g1b"/><path class="cbs471bbc"/><rect class="x1ju22b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ios-launcher" /></template>
<style>
.cbs471bbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.685 22.18v8.975m17.108-1.485c.83 1.082 1.873 1.485 3.322 1.485h2.005a3.38 3.38 0 0 0 3.38-3.38v-.014a3.38 3.38 0 0 0-3.38-3.38h-2.212a3.383 3.383 0 0 1-3.383-3.383a3.39 3.39 0 0 1 3.39-3.39h1.995c1.45 0 2.49.402 3.322 1.484");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.t1exc0g1b {
  cx: 11.685px;
  cy: 18.031px;
  r: 0.75px;
  fill: currentColor;
}

.x1ju22b0i {
  width: 8.975px;
  height: 13.547px;
  x: 15.909px;
  y: 17.607px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.487px;
  ry: 4.487px;
}

</style>
