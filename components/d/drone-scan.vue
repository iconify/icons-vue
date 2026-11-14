<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3mwx6lcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drone-scan" /></template>
<style>
.c3mwx6lcf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 5.5h1.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 12.75 9h-1.5A1.75 1.75 0 0 1 9.5 7.25a1.75 1.75 0 0 1 1.75-1.75M9.5 7.25H5V3.5m9.5 3.75H19V3.5m-16.5 0h5m9 0h5M9.5 12L5 20.5m9.5-8.5l4.5 8.5m-11.5-4h9");
}

</style>
