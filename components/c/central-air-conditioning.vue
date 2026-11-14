<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r53g9k-oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:central-air-conditioning" /></template>
<style>
.r53g9k-oo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 5h11A3.5 3.5 0 0 1 21 8.5v1a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 9.5v-1A3.5 3.5 0 0 1 6.5 5m0 4h11M7 16c0 2 2 2 2 4m3-4c0 2 2 2 2 4m3-4c0 2 2 2 2 4");
}

</style>
