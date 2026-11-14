<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h-luh9b6x"/><path class="dt3udrbcs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crew-bag" /></template>
<style>
.dt3udrbcs {
  d: path("M6.5 9.5c0-8 11-8 11 0");
}

.h-luh9b6x {
  d: path("M8.25 9.5h7.5A5.25 5.25 0 0 1 21 14.75v.5a5.25 5.25 0 0 1-5.25 5.25h-7.5A5.25 5.25 0 0 1 3 15.25v-.5A5.25 5.25 0 0 1 8.25 9.5m1.75 0v-1A1.5 1.5 0 0 1 11.5 7h1A1.5 1.5 0 0 1 14 8.5v1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
