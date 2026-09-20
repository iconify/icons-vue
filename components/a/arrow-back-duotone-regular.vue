<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u-kmlrghs"/><path class="g-zu73w3c"/><path class="sxlwlmkmh"/><path class="zuykpur_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-back-duotone-regular" /></template>
<style>
.g-zu73w3c {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 6 -6 6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sxlwlmkmh {
  d: path("M4 12h16");
}

.u-kmlrghs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zuykpur_s {
  d: path("m10 6 -6 6 6 6");
}

</style>
