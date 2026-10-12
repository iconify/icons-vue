<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="jgosbpbrm"/><circle class="ufbwiosyh"/><path class="pvjyt1bfs"/><path class="f6m5gbhvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:key-chain-sharp" /></template>
<style>
.f6m5gbhvl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.25 15.25l6 6m-3-3L16.5 20m3.5 0l-1.25 1.25");
}

.jgosbpbrm {
  cx: 7.25px;
  cy: 7.25px;
  r: 4.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pvjyt1bfs {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.6 11.6h.01");
}

.ufbwiosyh {
  cx: 12.75px;
  cy: 12.75px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
