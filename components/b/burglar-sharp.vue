<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="f3l_ylb3e"/><path class="bqud7pb8g"/><path class="m8kqe4bga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:burglar-sharp" /></template>
<style>
.bqud7pb8g {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 11.25h.01m4.99 0h.01");
}

.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.f3l_ylb3e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.95 6h14.1M6.5 9.25h11v4h-11z");
}

.m8kqe4bga {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 16.75h4");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
