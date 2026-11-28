<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bcje72bbx"/><path class="l1vguzbam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:crosshair-x-duotone" /></template>
<style>
.bcje72bbx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 12C21 16.9706 16.9706 21 12 21C7.0294 21 3 16.9706 3 12C3 7.0294 7.0294 3 12 3C16.9706 3 21 7.0294 21 12Z");
  stroke: none;
}

.l1vguzbam {
  d: path("M12 2V6M12 22V18M2 12H6M22 12H18M9.5 9.5L14.5 14.5M14.5 9.5L9.5 14.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
