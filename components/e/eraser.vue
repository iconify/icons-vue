<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da5pc3g_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser" /></template>
<style>
.da5pc3g_y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m15 16l5-5a1.414 1.414 0 0 0 0-2l-4-4a1.414 1.414 0 0 0-2 0l-5 5m2 10h10M9 10l6 6m-6-6l-5 5a1.414 1.414 0 0 0 0 2l3 3h4l4-4");
}

</style>
