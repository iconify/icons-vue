<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k44ucwlod"/><path class="tgth1rbuy"/><path class="wxng3f21w"/><path class="jdxsdlola"/><path class="awxqv1b4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:carbon-footprint-outline-regular" /></template>
<style>
.awxqv1b4c {
  d: path("M17 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.jdxsdlola {
  d: path("M14 3.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.k44ucwlod {
  d: path("M7 11a5 5 0 0 1 10 0v6a5 5 0 0 1 -10 0Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tgth1rbuy {
  d: path("M6 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.wxng3f21w {
  d: path("M10 3.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
