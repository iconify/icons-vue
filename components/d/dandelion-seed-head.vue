<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klluzmk8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dandelion-seed-head" /></template>
<style>
.klluzmk8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 2v10m0-14v-5M13.5 8L17 4.5m-3 5h4.75M10 9.5H5.25M10.5 8L7 4.5m3.5 6.5L7 14.5m3.75-11.75a7 7 0 0 1 2.5 0m2.75 1a7 7 0 0 1 1.75 1.75m1 2.75a7 7 0 0 1 0 2.5m-13.5 0a7 7 0 0 1 0-2.5m1-2.75A7 7 0 0 1 8 3.75m0 11.5a7 7 0 0 1-1.75-1.75M15 17l3-3m-1.25-1.25l2.5 2.5");
}

</style>
