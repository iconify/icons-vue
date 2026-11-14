<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2u-i_h9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bar-stool" /></template>
<style>
.r2u-i_h9x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7a6 2.5 0 1 0 12 0A6 2.5 0 1 0 6 7m6 2.5v10M7 21l5-4l5 4m-9-6.5h8");
}

</style>
