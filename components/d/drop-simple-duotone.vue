<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="z88gdpbil"/><path class="azrxifb0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:drop-simple-duotone" /></template>
<style>
.azrxifb0i {
  d: path("M174 47.75a254.2 254.2 0 0 0-41.45-38.3a8 8 0 0 0-9.18 0A254.2 254.2 0 0 0 82 47.75C54.51 79.32 40 112.6 40 144a88 88 0 0 0 176 0c0-31.4-14.51-64.68-42-96.25M128 216a72.08 72.08 0 0 1-72-72c0-57.23 55.47-105 72-118c16.53 13 72 60.75 72 118a72.08 72.08 0 0 1-72 72");
}

.cuyn6tgcc {
  fill: currentColor;
}

.z88gdpbil {
  d: path("M208 144a80 80 0 0 1-160 0c0-72 80-128 80-128s80 56 80 128");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
