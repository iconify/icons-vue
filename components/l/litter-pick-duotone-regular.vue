<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h5q2t-n9y"/><path class="tns1-ur3v"/><path class="nqbub38-r"/><path class="bcqk9b5zt"/><path class="bm-drdp9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:litter-pick-duotone-regular" /></template>
<style>
.bcqk9b5zt {
  d: path("m13 13 3 3");
}

.bm-drdp9q {
  d: path("M8 19h6v3H8Z");
}

.h5q2t-n9y {
  fill: currentColor;
  d: path("M8 19h6v3H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nqbub38-r {
  d: path("m13 13 -3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tns1-ur3v {
  d: path("m4 4 9 9");
}

</style>
