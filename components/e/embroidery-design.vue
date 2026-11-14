<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cc_5zk4eo"/><path class="nzesupbbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:embroidery-design" /></template>
<style>
.cc_5zk4eo {
  d: path("M3.25 12.75a8.75 8.75 0 1 0 17.5 0a8.75 8.75 0 1 0-17.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nzesupbbl {
  d: path("M10.5 4.25v-2h3v2m-3 6.5a2.25 2.25 0 1 1 3 0a2.25 2.25 0 1 1 1 2.75a2.25 2.25 0 1 1-2.5 1.75a2.25 2.25 0 1 1-2.5-1.75a2.25 2.25 0 1 1 1-2.75");
}

</style>
