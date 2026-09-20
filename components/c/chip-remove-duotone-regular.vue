<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vrvtjpall"/><path class="mjmmdiava"/><path class="v22s1vbap"/><path class="k_916xngw"/><path class="x3gr8qf4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chip-remove-duotone-regular" /></template>
<style>
.k_916xngw {
  d: path("m14.5 10.5 3 3");
}

.mjmmdiava {
  d: path("M3 12a4 4 0 0 1 4 -4h10a4 4 0 0 1 4 4 4 4 0 0 1 -4 4H7a4 4 0 0 1 -4 -4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v22s1vbap {
  d: path("M6.5 12H11");
}

.vrvtjpall {
  fill: currentColor;
  d: path("M3 12a4 4 0 0 1 4 -4h10a4 4 0 0 1 4 4 4 4 0 0 1 -4 4H7a4 4 0 0 1 -4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x3gr8qf4w {
  d: path("m17.5 10.5 -3 3");
}

</style>
