<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="sulf22bsc"/><path class="l92vy6b4v"/><path class="pkxclebiu"/><path class="rmg-mntjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baby-heart-sharp" /></template>
<style>
.l92vy6b4v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.75h-1.75V6.5h1.25");
}

.pkxclebiu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 11.5h.01m5.99 0h.01");
}

.rmg-mntjj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 15.5L12 17.3l2.25-1.8");
}

.sulf22bsc {
  cx: 12px;
  cy: 12.5px;
  r: 8.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
