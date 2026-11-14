<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qlm9y60lx"/><path class="sgr4h-qkq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:audio-sync" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qlm9y60lx {
  d: path("M6 9.5h12a3.5 3.5 0 0 1 3.5 3.5v4.5A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5V13A3.5 3.5 0 0 1 6 9.5M2.5 8.125v-.166a1.5 1.5 0 0 1 1.181-1.466l14.622-3.178a1.5 1.5 0 0 1 1.78 1.128l.063.273a1.5 1.5 0 0 1-1.195 1.814L3.853 9.256A1.15 1.15 0 0 1 2.5 8.125");
}

.sgr4h-qkq {
  d: path("M5.5 15.25H8l1.5-2.75l2 5.5l2-5.5l2 5l1-2.25h2");
}

</style>
