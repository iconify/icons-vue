<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e54x5p4fq"/><path class="z-jimvq7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-plus-duocolor" /></template>
<style>
.e54x5p4fq {
  stroke-opacity: 0.4;
  d: path("M9 12h6m-3-3v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z-jimvq7n {
  d: path("m17 17l-4 4a1.414 1.414 0 0 1-2 0l-8-8a1.414 1.414 0 0 1 0-2l8-8a1.414 1.414 0 0 1 2 0l8 8a1.414 1.414 0 0 1 0 2z");
}

</style>
