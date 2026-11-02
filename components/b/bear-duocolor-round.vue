<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mlyae5b3r"/><path class="izxjarjel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bear-duocolor-round" /></template>
<style>
.izxjarjel {
  d: path("M5 9C3 6.333 7 3.333 9 6q3-1.5 6 0c2-2.667 6 .333 4 3c2 3 2 6 1 8c-1 3-4 4-8 4s-7-1-8-4c-1-2-1-5 1-8");
}

.mlyae5b3r {
  stroke-opacity: 0.4;
  d: path("M9 12h.01M15 12h.01M11 16h2l-1 1Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
