<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4j6mybmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:head-heart" /></template>
<style>
.l4j6mybmz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 21v-3c-3-2-4-5-4-8c0-4 3-7 7-7s7 3 7 7l3 4h-3v4h-4v3Zm3-11c0-2-4-3-4 0c0 2 4 5 4 5s4-3 4-5c0-3-4-2-4 0");
}

</style>
