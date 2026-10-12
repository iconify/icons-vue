<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p2ia_1bjv"/><path class="l1d_hpb_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:deep-space-network" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l1d_hpb_r {
  d: path("m9 11.5l3-3M6 21.25l3-4.1l3 4.1m1.03-15.57a3 3 0 0 1 1.79 1.79m-.77-4.61a6 6 0 0 1 3.59 3.59");
}

.p2ia_1bjv {
  d: path("m5 7.5l8 8a5.66 5.66 0 0 1-8-8");
}

</style>
