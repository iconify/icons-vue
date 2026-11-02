<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n12xakjal"/><path class="hr2w1v17t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser-sparkle-duocolor-sharp" /></template>
<style>
.hr2w1v17t {
  d: path("m15 16l6-6l-5-5l-6 6m0 0l-6 6l3 3h4l4-4m-4 4h10m-11-9l5 5");
}

.n12xakjal {
  stroke-opacity: 0.4;
  d: path("M6 3c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
