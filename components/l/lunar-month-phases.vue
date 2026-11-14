<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd2dgpbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lunar-month-phases" /></template>
<style>
.xd2dgpbbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 9a3 3 0 0 0 0 6a4.5 4.5 0 0 1 0-6M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0m9.5-3a3 3 0 0 1 0 6a4.5 4.5 0 0 0 0-6");
}

</style>
