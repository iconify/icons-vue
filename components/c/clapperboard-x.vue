<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ny04_mc-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clapperboard-x" /></template>
<style>
.ny04_mc-u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.6 20.5H3v-11h18v2.6M3.25 9.5L2.5 6l17-3l.75 3.5Zm5-4.75L10 8.25m3.5-4.5l1.75 3.5m.25 8.25l5 5m0-5l-5 5");
}

</style>
