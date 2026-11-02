<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpsy1qb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dribbble-round" /></template>
<style>
.lpsy1qb7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 4c5 6 7 10 8 16M4 11c4.5 0 9-1 14-5M7 19c3-3 6-6 13-7M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0");
}

</style>
