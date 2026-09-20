<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c13n5ccfl"/><path class="n09nomjwg"/><path class="qp8kb8bwr"/><path class="z4xd2x6yx"/><path class="e7q8l6x6g"/><path class="osdsz4bam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:configmap-duotone-regular" /></template>
<style>
.c13n5ccfl {
  fill: currentColor;
  d: path("M15 6h3a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.e7q8l6x6g {
  d: path("M6 14h5");
}

.n09nomjwg {
  d: path("M15 6h3a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.osdsz4bam {
  d: path("M13 14h5");
}

.qp8kb8bwr {
  d: path("M6 10h5");
}

.z4xd2x6yx {
  d: path("M13 10h5");
}

</style>
