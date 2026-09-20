<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pxb3oacsp"/><path class="b5wqv3c3i"/><path class="nudzxvbtj"/><path class="ojebq65vr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:engine-duotone-regular" /></template>
<style>
.b5wqv3c3i {
  d: path("M2 13a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nudzxvbtj {
  d: path("M6 11V6h4v5");
}

.ojebq65vr {
  d: path("M13 11V4h4v7");
}

.pxb3oacsp {
  fill: currentColor;
  d: path("M2 13a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
