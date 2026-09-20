<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xtqbfpzcr"/><path class="ior14cbcm"/><path class="euvekjzkt"/><path class="a7rs12ltr"/><path class="k15q4tbdt"/><path class="z9ittvbis"/><path class="bnhdslb0j"/><path class="vl804rbny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dawn-duotone-thin" /></template>
<style>
.a7rs12ltr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16.5 10.5 19 8l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bnhdslb0j {
  d: path("M19 8v6");
}

.euvekjzkt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ior14cbcm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k15q4tbdt {
  d: path("M6 19a6 6 0 0 1 12 0");
}

.vl804rbny {
  d: path("M16.5 10.5 19 8l2.5 2.5");
}

.xtqbfpzcr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 19a6 6 0 0 1 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
