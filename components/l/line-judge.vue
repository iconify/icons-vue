<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eznyxhsqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:line-judge" /></template>
<style>
.eznyxhsqy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0M3 21.5v-4C3 15 5.5 13 8.5 13s5.5 2 5.5 4.5v4m3.5-19V15M19 3h1a1.5 1.5 0 0 1 1.5 1.5V7A1.5 1.5 0 0 1 20 8.5h-1A1.5 1.5 0 0 1 17.5 7V4.5A1.5 1.5 0 0 1 19 3");
}

</style>
