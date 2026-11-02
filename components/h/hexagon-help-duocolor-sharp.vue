<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="izd9lacbg"/><path class="p8fnjac2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-help-duocolor-sharp" /></template>
<style>
.izd9lacbg {
  stroke-opacity: 0.4;
  d: path("M10 11a2 2 0 1 1 2 2m0 3h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p8fnjac2o {
  d: path("M20 12v5l-8 4l-8-4V7l8-4l8 4z");
}

</style>
