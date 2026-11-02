<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajw79c8wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ambulance-sharp" /></template>
<style>
.ajw79c8wc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-9-7h4M8 9v4m-3 5H3V5h10v13m0-10h4l4 4v6h-2M9 18h6m-2-6h7");
}

</style>
