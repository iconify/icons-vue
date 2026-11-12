<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vxa2dmz6j"/><path class="dz4cxey5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-close-corner-duocolor-round" /></template>
<style>
.dz4cxey5t {
  d: path("M11 21H7a4 4 0 0 1-4-4V7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v4M3 17l4-4a2.83 2.83 0 0 1 4 0m3-5a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vxa2dmz6j {
  stroke-opacity: 0.4;
  d: path("m16 16l4 4m0-4l-4 4");
}

</style>
