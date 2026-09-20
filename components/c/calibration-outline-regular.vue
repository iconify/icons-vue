<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qe97cg-lx"/><path class="bd3-a5q0s"/><path class="c4o3x9bhp"/><path class="w9g5wtasy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:calibration-outline-regular" /></template>
<style>
.bd3-a5q0s {
  d: path("M6 18 18 6");
}

.c4o3x9bhp {
  d: path("M8 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qe97cg-lx {
  d: path("M3 3v18h18");
}

.w9g5wtasy {
  d: path("M14 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
