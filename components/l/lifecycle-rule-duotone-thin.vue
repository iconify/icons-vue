<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zrhfpjbsn"/><path class="n_mmwtwrp"/><path class="wh3qwbbqb"/><path class="cwmo4bc4s"/><path class="m5wi144di"/><path class="nk1txyodw"/><path class="o7fu1nbtq"/><path class="eus9a2f4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lifecycle-rule-duotone-thin" /></template>
<style>
.cwmo4bc4s {
  d: path("M3 5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
}

.eus9a2f4d {
  d: path("M16.5 12.5 19 15l2.5 -2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m5wi144di {
  d: path("M3 12a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
}

.n_mmwtwrp {
  fill: currentColor;
  d: path("M3 12a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nk1txyodw {
  d: path("M3 19a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
}

.o7fu1nbtq {
  d: path("M19 5v10");
}

.wh3qwbbqb {
  fill: currentColor;
  d: path("M3 19a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zrhfpjbsn {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
