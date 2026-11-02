<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="abwcm3cmh"/><path class="rvgdyh45m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser-duocolor-sharp" /></template>
<style>
.abwcm3cmh {
  stroke-opacity: 0.4;
  d: path("m9 10l-6 6l4 4h4l4-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rvgdyh45m {
  d: path("m15 16l6-6l-6-6l-6 6m2 10h10M9 10l6 6");
}

</style>
