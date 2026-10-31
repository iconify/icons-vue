<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iu-1rnb9v"/><path class="zu379xpdv"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cigarette-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.iu-1rnb9v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 19L19 20.5C19 21.3284 18.3284 22 17.5 22L3.5 22C2.1193 22 1 20.8807 1 19.5L1 17.5C1 16.1193 2.1193 15 3.5 15L15 15L19 19Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zu379xpdv {
  stroke-opacity: 0.4;
  d: path("M10.151 4.4942C10.6341 3.9557 11.25 3.5301 11.9609 3.2714M16 3C17.6569 3 19 4.3431 19 6L19 7.5C20.6569 7.5 22 8.8431 22 10.5L22 12M19 7.5L17.5 7.5");
}

</style>
