<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jpe7lzmwk"/><path class="rs7ptrb0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cctv-duocolor-sharp" /></template>
<style>
.jpe7lzmwk {
  stroke-opacity: 0.4;
  d: path("M9 14a3 3 0 1 0 6 0a3 3 0 0 0-6 0m3 0h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rs7ptrb0g {
  d: path("M3 3h18v4H3Zm2 4v7a7 7 0 0 0 14 0V7");
}

</style>
