<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="da9tv37bc"/><path class="s1xpzm6ul"/><path class="oe5j32ktx"/><path class="ldnq4ecit"/><path class="g6e5e7bhp"/><path class="p4c11pbyi"/><path class="ng7_l5bbi"/><path class="qgimpuszh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:glacier-duotone-regular" /></template>
<style>
.da9tv37bc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m2 8 6 6 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g6e5e7bhp {
  d: path("m2 8 6 6 6 -6 6 6");
}

.ldnq4ecit {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ng7_l5bbi {
  d: path("m6 4 4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oe5j32ktx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p4c11pbyi {
  d: path("m2 15 6 6 6 -6 6 6");
}

.qgimpuszh {
  d: path("m14 4 4 4");
}

.s1xpzm6ul {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m2 15 6 6 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
