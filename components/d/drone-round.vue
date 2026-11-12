<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgmu767bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:drone-round" /></template>
<style>
.vgmu767bo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1Zm0-5a3.605 3.605 0 1 0-5 5m14 0a3.605 3.605 0 1 0-5-5m0 14a3.605 3.605 0 1 0 5-5M5 14a3.605 3.605 0 1 0 5 5M7 7l3 3m7-3l-3 3m-7 7l3-3m7 3l-3-3");
}

</style>
