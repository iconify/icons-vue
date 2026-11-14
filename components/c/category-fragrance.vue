<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv6b87bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-fragrance" /></template>
<style>
.zv6b87bkv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.871 2h4.258a1.5 1.5 0 0 1 1.06.439l1.457 1.457A1.2 1.2 0 0 1 17 4.75a1.2 1.2 0 0 1-.354.854l-1.457 1.457a1.5 1.5 0 0 1-1.06.439H9.871a1.5 1.5 0 0 1-1.06-.439L7.354 5.604A1.2 1.2 0 0 1 7 4.75a1.2 1.2 0 0 1 .354-.854l1.457-1.457A1.5 1.5 0 0 1 9.871 2m.629 5.5v3m3-3v3m-6 0h9A3.5 3.5 0 0 1 20 14v4a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 18v-4a3.5 3.5 0 0 1 3.5-3.5M10.25 2v5.5m3.5-5.5v5.5M4 14.5h16");
}

</style>
