<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndv0-6bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-clock-corner-round" /></template>
<style>
.ndv0-6bmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 9a4 4 0 0 0-4-4H7a4 4 0 0 0-4 4v6a4 4 0 0 0 4 4h2M3 9h18m-9 8a5 5 0 1 0 10 0a5 5 0 0 0-10 0m5-2v2h2");
}

</style>
