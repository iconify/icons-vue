<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r0jamibkm"/><path class="p4w7mzbtz"/><path class="bn_pu6j-z"/><path class="r5gr43bip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:folder-heart-duotone-regular" /></template>
<style>
.bn_pu6j-z {
  d: path("M20 7v13H4V4h5l3 3h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p4w7mzbtz {
  fill: currentColor;
  d: path("M8.5 12a1.75 1.75 0 0 1 3.5 0 1.75 1.75 0 0 1 3.5 0L12 15.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r0jamibkm {
  fill: currentColor;
  d: path("M20 7v13H4V4h5l3 3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r5gr43bip {
  d: path("M8.5 12a1.75 1.75 0 0 1 3.5 0 1.75 1.75 0 0 1 3.5 0L12 15.5Z");
}

</style>
