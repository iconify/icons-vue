<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcbvuimbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gas-engineer" /></template>
<style>
.dcbvuimbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M2.5 21c0-4.5 3-7 6-7c1.756 0 3.512.856 4.666 2.469M19 2.5A2.5 2.5 0 1 0 21.5 5m-4.25 1.75L14.5 9.5m4 4.5c2.5 2.25 3 3.5 3 5a3 3 0 0 1-6 0c0-1 .5-2 1.25-2.5c.25.75.75 1 1 1c0-1.25 0-2.25.75-3.5");
}

</style>
