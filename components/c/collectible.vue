<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vcrqayb4g"/><path class="wdabovbsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:collectible" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vcrqayb4g {
  d: path("M2.75 13.75a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

.wdabovbsb {
  d: path("M6 13.75a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0M18.75 2.5q0 2.75 2.75 2.75q-2.75 0-2.75 2.75q0-2.75-2.75-2.75q2.75 0 2.75-2.75");
}

</style>
