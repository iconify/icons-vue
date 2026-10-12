<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="r29buzb1t"/><path class="fx682i-nj"/><path class="poxds44nh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-thinking-sharp" /></template>
<style>
.fx682i-nj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 9.5h.01m5.49 0h.01");
}

.poxds44nh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.75 6.5l2.5-.75m-2.75 8l2.75-.5M7.5 16.5h2v-1.1l.106-1.12h2.25l-.106 1.12v5.85H5.5V17h2Z");
}

.r29buzb1t {
  cx: 12px;
  cy: 11px;
  r: 8px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
