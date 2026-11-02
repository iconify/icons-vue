<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olv8kndyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-2" /></template>
<style>
.olv8kndyu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20h18M5 20v-8c0-.64.36-1.36 1-2l5-5a1.414 1.414 0 0 1 2 0l5 5c.64.64 1 1.36 1 2v8m-9 0v-4a2 2 0 1 1 4 0v4");
}

</style>
