<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_6cslb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-heatmap-round" /></template>
<style>
.y_6cslb0b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v10a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm9-4v18m-9-9h18M6 7a1 1 0 1 0 2 0a1 1 0 0 0-2 0m11 0h.01M16 17a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
