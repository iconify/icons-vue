<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a742oib1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-grab-duocolor-sharp" /></template>
<style>
.a742oib1c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 12V9a2 2 0 1 1 4 0V8a2 2 0 1 1 4 0v1a2 2 0 1 1 4 0v6a6 6 0 0 1-6 6h-4a6 6 0 0 1-6-6v-3a2 2 0 1 1 4 0m4-3v3m4-3v3m-8 0v3");
}

</style>
