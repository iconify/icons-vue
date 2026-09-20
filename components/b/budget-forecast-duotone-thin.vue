<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mliavyjyi"/><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="bg5rtlbxj"/><path class="uklz8h1xv"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="x9ne0caxf"/><path class="ks612kq_w"/><path class="boj5jfb_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:budget-forecast-duotone-thin" /></template>
<style>
.bg5rtlbxj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 8h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.boj5jfb_k {
  d: path("M13.5 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.gms_xv68n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ks612kq_w {
  d: path("m7 17 5 -5");
}

.mliavyjyi {
  fill: currentColor;
  d: path("M13.5 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.uklz8h1xv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 17 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x9ne0caxf {
  d: path("M7 8h12");
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
