<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zhy5nnbig"/><path class="f8es0kdly"/><path class="lvy4ugbrg"/><path class="o_ssmh9ez"/><path class="bok4-ne0z"/><path class="ik3tfcbzx"/><path class="sim8sii7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:compound-interest-duotone-regular" /></template>
<style>
.bok4-ne0z {
  d: path("m8 16 8 -8");
}

.f8es0kdly {
  fill: currentColor;
  d: path("M7 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ik3tfcbzx {
  d: path("M7 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.lvy4ugbrg {
  fill: currentColor;
  d: path("M13 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o_ssmh9ez {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

.sim8sii7h {
  d: path("M13 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zhy5nnbig {
  fill: currentColor;
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
