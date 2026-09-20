<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u-kmlrghs"/><path class="ys95wsbzg"/><path class="i0lroi0ex"/><path class="sxlwlmkmh"/><path class="hzsvawc8s"/><path class="u8aszkb6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-left-right-duotone-regular" /></template>
<style>
.hzsvawc8s {
  d: path("m8 8 -4 4 4 4");
}

.i0lroi0ex {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 8 4 4 -4 4");
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

.u8aszkb6i {
  d: path("m16 8 4 4 -4 4");
}

.ys95wsbzg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 8 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
