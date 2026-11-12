<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdaac-b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:key-sync-corner-round" /></template>
<style>
.gdaac-b1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 9a2.828 2.828 0 1 0-4 4a2.828 2.828 0 0 0 4-4m0 0l6-6m-2.128 2.129l2 2M13 4l2 2m5 12a4.472 4.472 0 0 1-8 0m0 3v-3h3m-3-4a4.472 4.472 0 0 1 8 0m0-3v3h-3");
}

</style>
