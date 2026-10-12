<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="i84_-sbbe"/><path class="inichvbyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-turn-down-sharp" /></template>
<style>
.i84_-sbbe {
  d: path("M6.25 4.25a8 8 0 0 1 8 8v7");
}

.inichvbyb {
  d: path("m10.5 15.5l3.75 3.75L18 15.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
