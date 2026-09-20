<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="k3wz1r14d"/><path class="yrx0yqkaa"/><path class="s626aibeg"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="x0cr3vblz"/><path class="d-23-qb2d"/><path class="gacdnhbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-column-increasing-duotone-thin" /></template>
<style>
.d-23-qb2d {
  d: path("M13 11v9");
}

.gacdnhbnq {
  d: path("M18 7v13");
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

.k3wz1r14d {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 15v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.s626aibeg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 7v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x0cr3vblz {
  d: path("M8 15v5");
}

.yrx0yqkaa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 11v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
