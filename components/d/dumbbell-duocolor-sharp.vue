<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lz692cbkn"/><path class="c38dkhcpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dumbbell-duocolor-sharp" /></template>
<style>
.c38dkhcpo {
  d: path("M5 5h4v14H5Zm10 0h4v14h-4ZM5 8H3v8h2m14-8h2v8h-2");
}

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

</style>
