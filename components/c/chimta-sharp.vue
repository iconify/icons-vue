<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="sb4kn6-oq"/><path class="dpexgjbks"/><path class="lrp22rkqr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chimta-sharp" /></template>
<style>
.dpexgjbks {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.47 6.04L7.5 21m6.03-14.96L16.5 21");
}

.lrp22rkqr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 13h.01m12.49 0h.01");
}

.sb4kn6-oq {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
