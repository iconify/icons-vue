<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pus9z-bwo"/><path class="r64foyb_z"/><path class="i6z46-gcv"/><path class="tyihvpb9r"/><path class="kodna-rjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:expert-router-outline-regular" /></template>
<style>
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

.tyihvpb9r {
  d: path("M2.5 15a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

</style>
