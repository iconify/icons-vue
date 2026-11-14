<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0xsx1byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hive-box" /></template>
<style>
.s0xsx1byi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 3.5h13.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 18.75 7H5.25A1.75 1.75 0 0 1 3.5 5.25A1.75 1.75 0 0 1 5.25 3.5M6.5 7h11A1.5 1.5 0 0 1 19 8.5v3a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 11.5v-3A1.5 1.5 0 0 1 6.5 7m0 6h11a1.5 1.5 0 0 1 1.5 1.5v4a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 18.5v-4A1.5 1.5 0 0 1 6.5 13m0 7v1.5m11-1.5v1.5m-7.5-4h4");
}

</style>
