<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w30nbkbiw"/><path class="p8fnjac2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-warning-duocolor-sharp" /></template>
<style>
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

.w30nbkbiw {
  stroke-opacity: 0.4;
  d: path("M12 9v4m0 3h.01");
}

</style>
