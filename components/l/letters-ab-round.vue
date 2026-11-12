<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej1spybqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letters-ab-round" /></template>
<style>
.ej1spybqz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 18L7 6l4 12m-7-3h6m5-9v12h3a3 3 0 0 0 0-6h-3m0-6h3a3 3 0 0 1 0 6");
}

</style>
