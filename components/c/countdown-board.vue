<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m34mgmf7q"/><path class="xemv4mmib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:countdown-board" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m34mgmf7q {
  d: path("M5.125 3.5h13.75A2.625 2.625 0 0 1 21.5 6.125v7.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 13.875v-7.75A2.625 2.625 0 0 1 5.125 3.5M7 16.5v4m10-4v4");
}

.xemv4mmib {
  d: path("M9.5 6.75h5L12 9.5c1.75 0 2.75 1 2.75 2.25s-1 2-2.5 2c-1.25 0-2.25-.5-2.75-1.25");
}

</style>
