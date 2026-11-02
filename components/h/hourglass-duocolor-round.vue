<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yvebdkb2o"/><path class="dufm80bmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hourglass-duocolor-round" /></template>
<style>
.dufm80bmi {
  d: path("M7 3v2c0 1.28.36 2.36 1 3l4 4l-4 4c-.64.64-1 1.72-1 3v2M17 3v2c0 1.28-.36 2.36-1 3l-4 4l4 4c.64.64 1 1.72 1 3v2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yvebdkb2o {
  stroke-opacity: 0.4;
  d: path("M5 3h14M5 21h14");
}

</style>
