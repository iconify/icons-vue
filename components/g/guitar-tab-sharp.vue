<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zc71pfbjn"/><circle class="rsnkvx63x"/><path class="j8ly7-y-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:guitar-tab-sharp" /></template>
<style>
.j8ly7-y-w {
  d: path("m6.25 16.25l1.5 1.5");
}

.rsnkvx63x {
  cx: 10px;
  cy: 14px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zc71pfbjn {
  d: path("M13.96 14.63a5.25 5.25 0 1 1-4.59-4.59a3.75 3.75 0 1 1 4.59 4.59Zm5.82-11.12l.71.71l.53.53l-.53.53l-1.41 1.41l-.53.53l-.53-.53l-.71-.71l-.53-.53l.53-.53l1.41-1.41l.53-.53zm-6.03 6.74l4.1-4.1");
}

</style>
