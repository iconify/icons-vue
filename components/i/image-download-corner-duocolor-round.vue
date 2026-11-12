<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pkbl_6tlo"/><path class="dz4cxey5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-download-corner-duocolor-round" /></template>
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

.pkbl_6tlo {
  stroke-opacity: 0.4;
  d: path("m15 18l3 3l3-3m-3 3v-6");
}

</style>
