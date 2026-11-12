<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0fk8kb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:binoculars-round" /></template>
<style>
.x0fk8kb-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 16a3 3 0 1 0 6 0a3 3 0 0 0-6 0m12 0a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-6-5h6M3 16c0-3 4-6 4-8V7a1 1 0 0 1 2 0v9m12 0c0-3-4-6-4-8V7a1 1 0 0 0-2 0v9");
}

</style>
