<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><path class="hw_1n2lss"/><path class="qtu1uub8p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:depth-map-sharp" /></template>
<style>
.hw_1n2lss {
  d: path("M8.5 7H17v10H7V7zM3.6 3.6l3.8 3.8m13-3.8l-3.8 3.8m3.8 13l-3.8-3.8m-13 3.8l3.8-3.8");
}

.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.qtu1uub8p {
  d: path("M10.25 10.25h3.5v3.5h-3.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
