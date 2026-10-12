<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="pfz5sybjk"/><path class="dd_6j-l0z"/><path class="q6_9d_o1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:frown-sharp" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.dd_6j-l0z {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 11h.01M15 11h.01");
}

.pfz5sybjk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8H10m4 0h2.5");
}

.q6_9d_o1t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.5 16.75l1.467-1.1h4.066l1.467 1.1");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
