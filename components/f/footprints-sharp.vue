<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbgycnb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:footprints-sharp" /></template>
<style>
.bbgycnb6b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 17V9c0-3 1-4 3-4c3 0 4 2 4 4c0 3-2 4-2 7v5H3zm18-2V7c0-3-1-4-3-4c-3 0-4 2-4 4c0 3 2 4 2 7v5h5zM3 17h5m13-2h-5");
}

</style>
