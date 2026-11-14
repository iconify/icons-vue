<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wloksqbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beard-trimmer" /></template>
<style>
.wloksqbts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 5.5h7.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 15.75 9h-7.5A1.75 1.75 0 0 1 6.5 7.25A1.75 1.75 0 0 1 8.25 5.5M8 9v10a2.5 2.5 0 0 0 2.5 2.5h3A2.5 2.5 0 0 0 16 19V9M8.5 2.5v3m3.5-3v3m3.5-3v3");
}

</style>
