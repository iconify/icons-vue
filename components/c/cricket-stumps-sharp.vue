<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="oyj4iebvj"/><circle class="ts3nldyxi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cricket-stumps-sharp" /></template>
<style>
.oyj4iebvj {
  d: path("m13.14 9.8l1.06 1.06l1.24 1.24l-1.24 1.24l-6.36 6.36l-1.24 1.24l-1.24-1.24l-1.06-1.06l-1.24-1.24l1.24-1.24l6.36-6.36l1.24-1.24zm.61.45l5-5");
}

.ts3nldyxi {
  cx: 17.75px;
  cy: 16.75px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
