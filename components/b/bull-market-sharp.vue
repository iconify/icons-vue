<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="adjw24blj"/><path class="fk62mkb-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bull-market-sharp" /></template>
<style>
.adjw24blj {
  d: path("M5.25 9.75h13.5v11.5H5.25z");
}

.fk62mkb-e {
  d: path("M5.25 12.5C2.5 11.5 2 6 7.5 4.75m11.25 7.75C21.5 11.5 22 6 16.5 4.75M8.25 17.5l2.5-2.5l2 2l3-3m-2.5 0h2.5v2.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
