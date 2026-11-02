<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itjarsw2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ambulance-round" /></template>
<style>
.itjarsw2m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-9-7h4M8 9v4m-3 5a2 2 0 0 1-2-2V9a4 4 0 0 1 4-4h3a3 3 0 0 1 3 3v10m0-10h3c.64 0 1.36.36 2 1l2 2c.64.64 1 1.36 1 2v3a2 2 0 0 1-2 2M9 18h6m-2-6h7");
}

</style>
