<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp0gn8nbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:goalie-blocker" /></template>
<style>
.rp0gn8nbg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.375 2.5h5.25A4.375 4.375 0 0 1 19 6.875v4.75A4.375 4.375 0 0 1 14.625 16h-5.25A4.375 4.375 0 0 1 5 11.625v-4.75A4.375 4.375 0 0 1 9.375 2.5M10.25 16h3.5a1.75 1.75 0 0 1 1.75 1.75v2a1.75 1.75 0 0 1-1.75 1.75h-3.5a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 10.25 16M8.5 18.75h7");
}

</style>
