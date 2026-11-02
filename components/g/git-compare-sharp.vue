<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfm9_xbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-compare-sharp" /></template>
<style>
.rfm9_xbey {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m14 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2-2V6h-8m3-3l-3 3l3 3M5 8v10h8m-3-3l3 3l-3 3");
}

</style>
