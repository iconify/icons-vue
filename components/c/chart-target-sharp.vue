<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="el43kubea"/><circle class="o4t0kqbkr"/><path class="qir7ovodz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-target-sharp" /></template>
<style>
.el43kubea {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12.75h3.5v7.5h-3.5zm6.5-7h3.5v14.5h-3.5zm6.5 8.5h3.5v6h-3.5zm-14-5.5H16.5");
}

.o4t0kqbkr {
  cx: 19.25px;
  cy: 8.75px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qir7ovodz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.25 8.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
