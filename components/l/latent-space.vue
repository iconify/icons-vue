<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="txr5qfbtf"/><circle class="cx8dycbip"/><circle class="aru5o0b-z"/><circle class="vfirqw8mn"/><circle class="beel-rkvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:latent-space" /></template>
<style>
.aru5o0b-z {
  cx: 17.5px;
  cy: 5.75px;
  r: 1.25px;
}

.beel-rkvu {
  cx: 18px;
  cy: 11px;
  r: 1.25px;
}

.cx8dycbip {
  cx: 13.25px;
  cy: 9.75px;
  r: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.txr5qfbtf {
  d: path("M8 15.5V3.25M8 15.5h12.75M8 15.5l-5 5");
}

.vfirqw8mn {
  cx: 12.75px;
  cy: 4.5px;
  r: 1.25px;
}

</style>
