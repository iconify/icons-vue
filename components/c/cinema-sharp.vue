<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="z-l-m0bjt"/><path class="gtmwntbok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cinema-sharp" /></template>
<style>
.gtmwntbok {
  d: path("m10.75 6.75l3.5 1.75l-3.5 1.75ZM4 17.5q8-2.5 16 0m-17 3q9-2.5 18 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z-l-m0bjt {
  d: path("M3 4h18v9H3z");
}

</style>
