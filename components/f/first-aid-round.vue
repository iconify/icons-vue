<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adszbn4wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:first-aid-round" /></template>
<style>
.adszbn4wz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 9h3a3 3 0 0 1 0 6h-3v3a3 3 0 0 1-6 0v-3H6a3 3 0 0 1 0-6h3V6a3 3 0 0 1 6 0z");
}

</style>
