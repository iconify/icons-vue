<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tb3jx___w"/><circle class="rsi23vbic"/><path class="nf7ntvb4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-seat-baby-sharp" /></template>
<style>
.nf7ntvb4j {
  d: path("m8.5 15l5-3.5m-10 8.75q8.5 1.5 17 0");
}

.rsi23vbic {
  cx: 10px;
  cy: 8.5px;
  r: 2px;
}

.tb3jx___w {
  d: path("M3.75 4.5H5.5V15h15v3H2.75V4.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
