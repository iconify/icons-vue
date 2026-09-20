<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k-xzyt36j"/><path class="y9nfs7b_r"/><path class="vsk4d-l1d"/><path class="p6ki6eqhw"/><path class="l2nbo7bgf"/><path class="m-p3hbclp"/><path class="exre5jj_d"/><path class="jwnes9bsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fuel-level-duotone-thin" /></template>
<style>
.exre5jj_d {
  d: path("m12 15 -4.5 -4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwnes9bsk {
  d: path("M8 19h8");
}

.k-xzyt36j {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 15a8 8 0 0 1 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l2nbo7bgf {
  d: path("M4 15a8 8 0 0 1 16 0");
}

.m-p3hbclp {
  d: path("M4 15h16");
}

.p6ki6eqhw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 19h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vsk4d-l1d {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 15 -4.5 -4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y9nfs7b_r {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 15h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
