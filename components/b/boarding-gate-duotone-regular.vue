<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m1mc0ac9n"/><path class="mir0zlume"/><path class="u6hhj794j"/><path class="wihs6r74z"/><path class="pnevpfb0l"/><path class="cq8r84bse"/><path class="srslrxb7v"/><path class="l90ci7bpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:boarding-gate-duotone-regular" /></template>
<style>
.cq8r84bse {
  d: path("M20 21V4h-4v17");
}

.l90ci7bpu {
  d: path("m12 9.5 2.5 2.5 -2.5 2.5");
}

.m1mc0ac9n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 21V4h4v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mir0zlume {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 21V4h-4v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pnevpfb0l {
  d: path("M4 21V4h4v17");
}

.srslrxb7v {
  d: path("M10 12h4.5");
}

.u6hhj794j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 12h4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wihs6r74z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 9.5 2.5 2.5 -2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
