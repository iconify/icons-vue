<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7q5yjvqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:action-recognition" /></template>
<style>
.p7q5yjvqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-2 7l4-2.25L16 12m-4-2.25v5.75l-3 5m3-5l3 5m-9.343-6.191a6.75 6.75 0 0 1 0-4.618m-2.584 5.558a9.5 9.5 0 0 1 0-6.498m15.27.94a6.75 6.75 0 0 1 0 4.618m2.584-5.558a9.5 9.5 0 0 1 0 6.498");
}

</style>
