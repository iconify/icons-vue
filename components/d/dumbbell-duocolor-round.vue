<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lz692cbkn"/><path class="qq0wkvb9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dumbbell-duocolor-round" /></template>
<style>
.lz692cbkn {
  stroke-opacity: 0.4;
  d: path("M9 12h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qq0wkvb9d {
  d: path("M5 7a2 2 0 1 1 4 0v10a2 2 0 1 1-4 0Zm10 0a2 2 0 1 1 4 0v10a2 2 0 1 1-4 0ZM5 8a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2m14-8a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2");
}

</style>
