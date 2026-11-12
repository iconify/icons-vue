<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e08679bhk"/><path class="u78g8rg8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:eye-closed-line-duotone" /></template>
<style>
.e08679bhk {
  d: path("M2 7C2 7 5 14 12 14C13.34 14 14.5334 13.7435 15.5872 13.3287C16.9547 12.7904 18.0872 11.9856 19 11.1288C21.0586 9.19661 22 7 22 7");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u78g8rg8y {
  d: path("M12 14.0001V16.5001M15.5872 13.3288L17 15.5001M8.41281 13.3288L7 15.5001M19 11.1289L20.5 12.6289M5 11.1289L3.5 12.6289");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
