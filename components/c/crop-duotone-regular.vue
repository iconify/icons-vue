<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r6_u0sb_e"/><path class="n3vgmpbfl"/><path class="p7np2t4-r"/><path class="kk-ohg6gv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:crop-duotone-regular" /></template>
<style>
.kk-ohg6gv {
  d: path("M2 6h16v16");
}

.n3vgmpbfl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 6h16v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p7np2t4-r {
  d: path("M6 2v16h16");
}

.r6_u0sb_e {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 2v16h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
