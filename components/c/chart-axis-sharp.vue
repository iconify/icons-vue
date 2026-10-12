<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ijcbndbsu"/><circle class="s7r9jey2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-axis-sharp" /></template>
<style>
.ijcbndbsu {
  d: path("M5.75 2.75v15.5h15.5M3.5 5l2.25-2.25L8 5m11 11l2.25 2.25L19 20.5m-8.25-2.25v3m5-3v3m-13-12.5h3m-3 4.5h3");
}

.s7r9jey2r {
  cx: 13.5px;
  cy: 10.25px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
