<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wk7q73bkt"/><path class="rlvj9fbpk"/><path class="ar1q9_ric"/><path class="pus9z-bwo"/><path class="r64foyb_z"/><path class="i6z46-gcv"/><path class="tyihvpb9r"/><path class="kodna-rjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:expert-router-duotone-regular" /></template>
<style>
.ar1q9_ric {
  fill: currentColor;
  d: path("M13.5 15a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.i6z46-gcv {
  d: path("m13.5 9 3 3");
}

.kodna-rjk {
  d: path("M13.5 15a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pus9z-bwo {
  d: path("m12 2 3 3 -3 3 -3 -3Z");
}

.r64foyb_z {
  d: path("m10.5 9 -3 3");
}

.rlvj9fbpk {
  fill: currentColor;
  d: path("M2.5 15a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tyihvpb9r {
  d: path("M2.5 15a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.wk7q73bkt {
  fill: currentColor;
  d: path("m12 2 3 3 -3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
