<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w10xa2b9e"/><path class="gqa7vck7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-download-duocolor-round" /></template>
<style>
.gqa7vck7h {
  d: path("M3 7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v10a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm0 10l1-1a4.243 4.243 0 0 1 6 0l5 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w10xa2b9e {
  stroke-opacity: 0.4;
  d: path("m11 10l3 3l3-3m-3 3V7");
}

</style>
