<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lrh9mnmxe"/><path class="aflr5rb0x"/><path class="jvmaqzbcd"/><circle class="nw5bhiu2a"/><circle class="hfexr3b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lona" /></template>
<style>
.aflr5rb0x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.542 17.637c-1.797-1.727-.272-4.765.704-5.506m1.684 8.376c-.918-2.714 3.434-6.246 6.526-5.232c1.296.425 3.161 4.31 3.038 8.128a2.5 2.5 0 0 1-.84 1.626");
}

.hfexr3b3y {
  cx: 9.2px;
  cy: 12.073px;
  r: 0.75px;
  fill: currentColor;
}

.jvmaqzbcd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.73 25.029c.581-2.967 6.93-2.638 7.925-1.036m-9.025 4.055c1.926-1.38 4.646.743 4.992 2.216m-7.923.635a3.46 3.46 0 0 1 3.517 3.37m-8.155-2.402c2.11.926 1.925 3.578 1.697 4.372m-6.24-6.405a3.03 3.03 0 0 1-.383 4.27m-1.798-7.611a3.25 3.25 0 0 1-.884 2.904m-.04-9.527a3.14 3.14 0 0 1-.88 2.917");
}

.lrh9mnmxe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.655 23.993a15.813 15.813 0 1 1-31.626.027v-.027a7.88 7.88 0 0 0-4.36-7.074a3.95 3.95 0 0 1 3.553-7.055a15.74 15.74 0 0 1 8.708 14.13a7.912 7.912 0 1 0 7.912-7.913h0a3.95 3.95 0 0 1 0-7.9a15.81 15.81 0 0 1 13.067 6.916");
}

.nw5bhiu2a {
  cx: 7.594px;
  cy: 14.316px;
  r: 0.75px;
  fill: currentColor;
}

</style>
