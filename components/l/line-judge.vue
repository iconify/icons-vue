<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6hzygbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:line-judge" /></template>
<style>
.w6hzygbwr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM3 21.5v-4C3 15 5.5 13 8.5 13s5.5 2 5.5 4.5v4m3.5-19V15m0-12h4v5.5h-4Z");
}

</style>
