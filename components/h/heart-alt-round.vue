<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvu1mm2xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heart-alt-round" /></template>
<style>
.hvu1mm2xr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 7l1-1a4.243 4.243 0 0 1 6 6l-4 4a4.243 4.243 0 0 1-6 0l-4-4a4.243 4.243 0 0 1 6-6z");
}

</style>
