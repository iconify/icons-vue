<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6adaobnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gift-tier-gold" /></template>
<style>
.y6adaobnv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 5.25h10.5A2.25 2.25 0 0 1 18 7.5a2.25 2.25 0 0 1-2.25 2.25H5.25A2.25 2.25 0 0 1 3 7.5a2.25 2.25 0 0 1 2.25-2.25m3 4.5h10.5A2.25 2.25 0 0 1 21 12a2.25 2.25 0 0 1-2.25 2.25H8.25A2.25 2.25 0 0 1 6 12a2.25 2.25 0 0 1 2.25-2.25m-2 4.5h10.5A2.25 2.25 0 0 1 19 16.5a2.25 2.25 0 0 1-2.25 2.25H6.25A2.25 2.25 0 0 1 4 16.5a2.25 2.25 0 0 1 2.25-2.25");
}

</style>
