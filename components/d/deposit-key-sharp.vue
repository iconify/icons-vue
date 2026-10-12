<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="tab64gb6d"/><path class="rxjktnbse"/><path class="g9yta1qci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:deposit-key-sharp" /></template>
<style>
.g9yta1qci {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 7.5h11m-3.75 0V10m3-2.5V10M8.75 12.75h12.5v8.5H8.75zm0 2.75h12.5m-12.5 3h12.5");
}

.rxjktnbse {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 7.5h.01");
}

.tab64gb6d {
  cx: 6.5px;
  cy: 7.5px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
