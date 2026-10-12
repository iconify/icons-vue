<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rfut0e6ix"/><circle class="ycarrlbsj"/><path class="qjt_-6-zx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eye-of-horus-sharp" /></template>
<style>
.qjt_-6-zx {
  d: path("M9 16.14V21m6-4.86l2 3.1a1.75 1.75 0 1 0 3.1-1.6");
}

.rfut0e6ix {
  d: path("M3 11.5c4-8.25 14-8.25 18 0c-4 6.75-14 6.75-18 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ycarrlbsj {
  cx: 12px;
  cy: 10.95px;
  r: 2.5px;
}

</style>
