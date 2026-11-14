<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zrodfgbbv"/><path class="v7cuadbon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cafe-counter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7cuadbon {
  d: path("M14 7h5v3.5a2.5 2.5 0 0 1-5 0Zm5 .5h1a1.25 1.25 0 0 1 0 2.5h-1");
}

.zrodfgbbv {
  d: path("M4.25 13h15.5a1.75 1.75 0 0 1 1.75 1.75v4a1.75 1.75 0 0 1-1.75 1.75H4.25a1.75 1.75 0 0 1-1.75-1.75v-4A1.75 1.75 0 0 1 4.25 13m-.75 0l1-5H10l1 5M7 4h.5a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 7.5 8H7a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 7 4");
}

</style>
