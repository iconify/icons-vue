<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjm92-bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cable" /></template>
<style>
.zjm92-bjt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7a2 2 0 0 1 2-2h4a2 2 0 1 1 0 4H5a2 2 0 0 1-2-2m10 10a2 2 0 0 1 2-2h4a2 2 0 1 1 0 4h-4a2 2 0 0 1-2-2M5 3v2m4-2v2m6 14v2m4-2v2M7 9v1a2 2 0 0 0 2 2h6a2 2 0 0 1 2 2v1");
}

</style>
