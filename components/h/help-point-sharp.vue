<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="obago5bid"/><path class="uaqvazbzh"/><path class="rl3f39odg"/><path class="x34_y0fwf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:help-point-sharp" /></template>
<style>
.obago5bid {
  cx: 12px;
  cy: 8.75px;
  r: 6px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rl3f39odg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.6h.01");
}

.uaqvazbzh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 7.25a2 2 0 1 1 2.9 1.8l-.9.491v1.209");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.x34_y0fwf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 14.75v6.5m-3.5 0h7");
}

</style>
