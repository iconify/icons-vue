<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l01xcbbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baking-tray" /></template>
<style>
.l01xcbbve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11.5h19l-2 4.5h-15Zm0 0C2.5 7 7 7 7 11.5m2.75 0c0-4.5 4.5-4.5 4.5 0m2.75 0c0-4.5 4.5-4.5 4.5 0");
}

</style>
