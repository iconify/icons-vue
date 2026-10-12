<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hsvbf9bcf"/><path class="d6q1-1ylw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-donut-sharp" /></template>
<style>
.d6q1-1ylw {
  d: path("M13.5 2.87a9.25 9.25 0 0 1 7.63 7.63h-4.62a4.75 4.75 0 0 0-3.01-3.01Z");
}

.hsvbf9bcf {
  d: path("M10.5 2.87A9.25 9.25 0 1 0 21.13 13.5h-4.62a4.75 4.75 0 1 1-6.01-6.01Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
