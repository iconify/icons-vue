<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m9lbe2bpd"/><path class="v-1g9bc9b"/><path class="bn5fnb4mk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fridge-collection" /></template>
<style>
.bn5fnb4mk {
  d: path("M4.5 19.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m11 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M3 7.5h8.5m-3 3V14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m9lbe2bpd {
  d: path("M5.625 3h3.25A2.625 2.625 0 0 1 11.5 5.625v9.25A2.625 2.625 0 0 1 8.875 17.5h-3.25A2.625 2.625 0 0 1 3 14.875v-9.25A2.625 2.625 0 0 1 5.625 3");
}

.v-1g9bc9b {
  d: path("M2.5 17.5h19v-4L18 10h-3.5v7.5");
}

</style>
