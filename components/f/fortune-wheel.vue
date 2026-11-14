<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="norsobbws"/><path class="wdmwffbwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fortune-wheel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.norsobbws {
  d: path("M5 14.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0M11.358 2h1.284a.822.822 0 0 1 .608 1.375l-.14.154a1.5 1.5 0 0 1-2.22 0l-.14-.154A.822.822 0 0 1 11.358 2");
}

.wdmwffbwu {
  d: path("M10 14.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m4 0h5m-9 0H5m8 1.75l2.5 4.25M11 16.25L8.5 20.5m2.5-7.75L8.5 8.5m4.5 4.25l2.5-4.25");
}

</style>
