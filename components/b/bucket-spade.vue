<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxzyziv-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bucket-spade" /></template>
<style>
.wxzyziv-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.066 8.5h8.868a1.75 1.75 0 0 1 1.726 2.038l-1.416 8.5a1.75 1.75 0 0 1-1.726 1.462H6.482a1.75 1.75 0 0 1-1.726-1.462l-1.416-8.5A1.75 1.75 0 0 1 5.066 8.5m-.566 0a5 5 0 0 1 10 0m3.5 6h3.5V18l-1.75 3L18 18Zm1.75 0V5m-1.5 0h3");
}

</style>
