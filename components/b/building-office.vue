<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7ejkwbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-office" /></template>
<style>
.x7ejkwbym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 21V7a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v14M3 21h18M8 9v4m4-4v4m4-4v4m-6 8v-2a2 2 0 1 1 4 0v2");
}

</style>
