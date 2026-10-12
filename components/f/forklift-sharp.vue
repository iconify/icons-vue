<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="e56suptyj"/><circle class="m_6c0ubwy"/><path class="bzy5_itsi"/><circle class="azeq682ld"/><path class="rsuow_bhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:forklift-sharp" /></template>
<style>
.azeq682ld {
  cx: 13.25px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.bzy5_itsi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 19h.01");
}

.e56suptyj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11.5h11.5v5.25H2.75zm2 0V4.75h5l2.5 6.75m5-8v13.25h4m-4-3.5h4");
}

.m_6c0ubwy {
  cx: 5.75px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rsuow_bhd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.25 19h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
