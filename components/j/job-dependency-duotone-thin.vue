<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgscl2bdj"/><path class="vws5wpblq"/><path class="d3jg_xb_z"/><path class="wwd4m5b_z"/><path class="ri2m-q_tv"/><path class="zirb-hbnv"/><path class="d_noaebcy"/><path class="d_yxl29go"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:job-dependency-duotone-thin" /></template>
<style>
.d_noaebcy {
  d: path("M10 12h6");
}

.d_yxl29go {
  d: path("M13.5 9.5 16 12l-2.5 2.5");
}

.d3jg_xb_z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ri2m-q_tv {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

.vws5wpblq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wwd4m5b_z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 9.5 16 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
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
