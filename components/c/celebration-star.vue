<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb-sblnxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:celebration-star" /></template>
<style>
.gb-sblnxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.455 6.185l.603 1.38a1.5 1.5 0 0 0 1.228.892l1.498.147a1.042 1.042 0 0 1 .59 1.817l-1.125.999a1.5 1.5 0 0 0-.469 1.444l.323 1.47a1.042 1.042 0 0 1-1.546 1.123l-1.298-.762a1.5 1.5 0 0 0-1.518 0l-1.298.762a1.042 1.042 0 0 1-1.546-1.123l.323-1.47a1.5 1.5 0 0 0-.469-1.444l-1.125-.999a1.042 1.042 0 0 1 .59-1.817l1.498-.147a1.5 1.5 0 0 0 1.228-.892l.603-1.38a1.042 1.042 0 0 1 1.91 0M3 21l3.5-3.5m-3.5-2L5.5 13");
}

</style>
