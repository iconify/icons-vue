<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ttd_wabxj"/><path class="p65z8acrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:exception-breakpoint" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p65z8acrr {
  fill: currentColor;
  d: path("M17 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.ttd_wabxj {
  d: path("m7.707 3.464l2.829 2.829a3 3 0 0 1 0 4.243a3 3 0 0 1-4.243 0L3.464 7.707a3 3 0 0 1 0-4.243a3 3 0 0 1 4.243 0m10 10l2.829 2.829a3 3 0 0 1 0 4.243a3 3 0 0 1-4.243 0l-2.829-2.829a3 3 0 0 1 0-4.243a3 3 0 0 1 4.243 0M10 14l-1.5 1.5M14 10l1.5-1.5");
}

</style>
