<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zds7z8bri"/><path class="eevklmbtb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:charging-station-duocolor" /></template>
<style>
.eevklmbtb {
  d: path("M3 5a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm10 7h2a2 2 0 0 1 2 2v1a2 2 0 1 0 4 0V8c0-.64-.36-1.36-1-2l-2-2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zds7z8bri {
  stroke-opacity: 0.4;
  d: path("m9 8l-3 4h4l-3 4");
}

</style>
