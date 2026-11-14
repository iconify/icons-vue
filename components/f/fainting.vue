<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezq3tibhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fainting" /></template>
<style>
.ezq3tibhj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.75 21.5l-1.25-3c-2.5-.5-4.25-2-5.25-3.75c-1.5-3.25 0-6.5 3-8c3-1.25 6-.5 7.5 2.25L17 11c.25.5.25 1-.25 1.25l-.5.25L17 14c.25.75 0 1.75-1 2.25l-1.25.5l1 2.25M20.5 2.5V8m-1.75-1.75L20.5 8L22 6.25");
}

</style>
