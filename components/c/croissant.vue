<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifa9g4bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:croissant" /></template>
<style>
.ifa9g4bjl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 18c-.75-1.25-1-2.5-1-3.5a9.5 9.5 0 0 1 19 0c0 1-.25 2.25-1 3.5c-1.25-1.5-2.75-2.5-4-2.75a4.5 4.5 0 0 0-9 0c-1.25.25-2.75 1.25-4 2.75M12 5v5.75M4.723 8.394l4.213 3.535m10.341-3.535l-4.213 3.535");
}

</style>
