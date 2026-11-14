<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmag2tsfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:basket-size" /></template>
<style>
.tmag2tsfm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.702 11h12.596a2.625 2.625 0 0 1 2.574 3.14l-.95 4.75A2.625 2.625 0 0 1 17.348 21H6.652a2.625 2.625 0 0 1-2.574-2.11l-.95-4.75A2.625 2.625 0 0 1 5.702 11M6 6.5h4A1.5 1.5 0 0 1 11.5 8v1.5A1.5 1.5 0 0 1 10 11H6a1.5 1.5 0 0 1-1.5-1.5V8A1.5 1.5 0 0 1 6 6.5m8 0h4A1.5 1.5 0 0 1 19.5 8v1.5A1.5 1.5 0 0 1 18 11h-4a1.5 1.5 0 0 1-1.5-1.5V8A1.5 1.5 0 0 1 14 6.5m-4-4h4A1.5 1.5 0 0 1 15.5 4v1A1.5 1.5 0 0 1 14 6.5h-4A1.5 1.5 0 0 1 8.5 5V4A1.5 1.5 0 0 1 10 2.5M8 14v4m4-4v4m4-4v4");
}

</style>
