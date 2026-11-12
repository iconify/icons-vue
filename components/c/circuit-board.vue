<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkljysf3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circuit-board" /></template>
<style>
.jkljysf3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm4 4a2 2 0 1 0 4 0a2 2 0 0 0-4 0m6 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-2-6h4a2 2 0 0 0 2-2V3m-4 12H9a2 2 0 0 0-2 2v4");
}

</style>
