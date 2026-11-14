<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m5scpk28v"/><path class="k5voygu2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-extract" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k5voygu2g {
  d: path("M4 13c0 1.4 3.6 2.5 8 2.5s8-1.1 8-2.5m-8 0V2.5M8.75 5.75L12 2.5l3.25 3.25");
}

.m5scpk28v {
  d: path("M4 13c0-1.4 3.6-2.5 8-2.5s8 1.1 8 2.5v6c0 1.4-3.6 2.5-8 2.5S4 20.4 4 19Z");
}

</style>
