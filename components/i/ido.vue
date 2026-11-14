<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pbki-cbad"/><path class="w5lfp4bxv"/><path class="duporv-yi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ido" /></template>
<style>
.duporv-yi {
  d: path("M18.75 17c-.25-.5-.5-.5-.75-.5q-.75 0-.75.75c0 .5 1.5.5 1.5 1.5q0 .75-.75.75c-.5 0-.75-.25-.75-.5m.75-3.25v.75m0 3v.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pbki-cbad {
  d: path("M9.5 2.5c3.25 2.5 4 6.5 3.25 11h-6.5C5.5 9 6.25 5 9.5 2.5");
}

.w5lfp4bxv {
  d: path("M6.25 9.5L3.5 12.25v2.25l2.75-1m6.5-4l2.333 2.333M9.5 16.5v4M14 18a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

</style>
