<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g0ql3bb1s"/><path class="d0ij1nb1u"/><path class="hosrnl1cs"/><path class="l9y5p1bzr"/><path class="eq8-mlt7s"/><path class="l0v-b4kbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dna-duotone-thin" /></template>
<style>
.d0ij1nb1u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 3c-8 4 -8 14 0 18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eq8-mlt7s {
  d: path("M16 3c-8 4 -8 14 0 18");
}

.g0ql3bb1s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 3c8 4 8 14 0 18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hosrnl1cs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

.l9y5p1bzr {
  d: path("M8 3c8 4 8 14 0 18");
}

</style>
