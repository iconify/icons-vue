<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m5vfg-38a"/><path class="dcivgm2wg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bulb-sparkle-duocolor" /></template>
<style>
.dcivgm2wg {
  d: path("M15 15v1a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2v-1c0-1.5-3-3.5-3-6a6 6 0 1 1 12 0c0 2.5-3 4.5-3 6m-6 6h6");
}

.m5vfg-38a {
  stroke-opacity: 0.4;
  d: path("M12 6c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
