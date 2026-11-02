<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajhk2sb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:luggage-round" /></template>
<style>
.ajhk2sb8d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19a2 2 0 0 1-2-2v-6a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v6a2 2 0 0 1-2 2m-6 0h2m-6 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0m6 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0M9 7V4a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v3");
}

</style>
