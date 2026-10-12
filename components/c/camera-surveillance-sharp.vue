<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><path class="r2lz8qbcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camera-surveillance-sharp" /></template>
<style>
.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.r2lz8qbcp {
  d: path("m7 7.5l8.5 2.75l-1 3L6 10.5Zm8.5 3.25l2 .75M10 12.75L9 16.5H6.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
