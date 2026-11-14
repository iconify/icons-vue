<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqavjvbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bidding-war" /></template>
<style>
.sqavjvbii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5h1A3.5 3.5 0 0 1 10.5 6A3.5 3.5 0 0 1 7 9.5H6A3.5 3.5 0 0 1 2.5 6A3.5 3.5 0 0 1 6 2.5m11 0h1A3.5 3.5 0 0 1 21.5 6A3.5 3.5 0 0 1 18 9.5h-1A3.5 3.5 0 0 1 13.5 6A3.5 3.5 0 0 1 17 2.5m-10.5 7l8 12m3-12l-8 12m-3-16.75v2.5m11-2.5v2.5");
}

</style>
