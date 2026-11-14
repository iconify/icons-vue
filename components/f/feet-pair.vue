<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyzbkobch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:feet-pair" /></template>
<style>
.jyzbkobch {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11.5c0-3.5 6.5-4 6.5 0L9.5 18A2.75 2.75 0 0 1 4 18Zm17 0c0-3.5-6.5-4-6.5 0l.5 6.5a2.75 2.75 0 0 0 5.5 0Zm-13-6.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M5 5.5h.01M14 4.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m5 .75h.01");
}

</style>
