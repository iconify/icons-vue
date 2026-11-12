<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy3jkpbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circuit-board-round" /></template>
<style>
.zy3jkpbjr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v10a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm4 2a2 2 0 1 0 4 0a2 2 0 0 0-4 0m6 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-2-6h2a4 4 0 0 0 4-4V3m-4 12h-2a4 4 0 0 0-4 4v2");
}

</style>
