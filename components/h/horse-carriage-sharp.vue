<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="jskzb-i1j"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="gy727-5xg"/><path class="my-8nir0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:horse-carriage-sharp" /></template>
<style>
.gy727-5xg {
  cx: 14.25px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jskzb-i1j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 16.75v-4.5c0-2.5 3-4 6.75-4s6.75 1.5 6.75 4v4.5Zm3.75-4.5h6m3.75.75h4");
}

.my-8nir0n {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.25 19h.01");
}

.ox2ue_b-w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19h.01");
}

.r_0b548wt {
  cx: 7px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
