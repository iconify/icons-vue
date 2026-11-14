<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6lrnwbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cursor-grab" /></template>
<style>
.v6lrnwbdz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 13.5v-5a1.5 1.5 0 0 1 3 0V6a1.5 1.5 0 0 1 3 0v.5a1.5 1.5 0 0 1 3 0v2a1.5 1.5 0 0 1 3 0V15c0 3.6-2.4 6-5.5 6h-1c-1.9 0-3.2-.9-4.25-2.5L4 14.5a1.5 1.5 0 0 1 2-1m3-5v3m3-5v5m3-3v3");
}

</style>
