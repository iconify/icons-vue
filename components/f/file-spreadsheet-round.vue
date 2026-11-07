<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="capil9boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-spreadsheet-round" /></template>
<style>
.capil9boy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H9a4 4 0 0 0-4 4v10a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4V9m-6-6l6 6m-6-6v4a2 2 0 0 0 2 2h4M8 13a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1Zm0 2h8m-5-3v6");
}

</style>
