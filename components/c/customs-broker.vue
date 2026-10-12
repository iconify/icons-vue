<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="w8khh1fqt"/><path class="esb6xlbba"/><rect class="x2sbelbil"/><path class="iqm9e0eeg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:customs-broker" /></template>
<style>
.esb6xlbba {
  d: path("M2.75 20.25a6.25 6.25 0 0 1 12.5 0a1 1 0 0 1-1 1H3.75a1 1 0 0 1-1-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iqm9e0eeg {
  d: path("M17.25 13h2m-2 3h2");
}

.w8khh1fqt {
  cx: 9px;
  cy: 7px;
  r: 3.75px;
}

.x2sbelbil {
  width: 6px;
  height: 11.5px;
  x: 15.25px;
  y: 9.75px;
  rx: 1px;
}

</style>
