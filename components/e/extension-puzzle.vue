<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scg7f0b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:extension-puzzle" /></template>
<style>
.scg7f0b6b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.5h5.25a2.5 2.5 0 0 1 5 0H18v4.25a2.5 2.5 0 0 1 0 5V21h-4.25a2.5 2.5 0 0 0-5 0H3.5Z");
}

</style>
