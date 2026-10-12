<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wcjb1xbey"/><path class="lhe0s9blf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:day-night-sharp" /></template>
<style>
.lhe0s9blf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.75 5.25h.01M20.25 9h.01m-1.51 9.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wcjb1xbey {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 6.75a5.25 5.25 0 0 0 0 10.5Zm1.75 0a5.25 5.25 0 0 1 0 10.5a7.9 7.9 0 0 0 0-10.5Zm-1.75-4v1.5m0 15.5v1.5M2.75 12h1.5m.96-6.29l1.06 1.06M5.21 18.29l1.06-1.06");
}

</style>
