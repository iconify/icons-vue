<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xgscl2bdj"/><path class="n5v54kp1e"/><path class="ik2mn1hhf"/><path class="rcex2je1b"/><path class="ri2m-q_tv"/><path class="zirb-hbnv"/><path class="d_noaebcy"/><path class="d_yxl29go"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:job-dependency-duotone-regular" /></template>
<style>
.d_noaebcy {
  d: path("M10 12h6");
}

.d_yxl29go {
  d: path("M13.5 9.5 16 12l-2.5 2.5");
}

.ik2mn1hhf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n5v54kp1e {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rcex2je1b {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 9.5 16 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ri2m-q_tv {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

.xgscl2bdj {
  fill: currentColor;
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zirb-hbnv {
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
