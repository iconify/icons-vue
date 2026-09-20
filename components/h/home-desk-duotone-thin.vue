<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ii4t72bxj"/><path class="fdv44xbzc"/><path class="yb_89281i"/><path class="qggih1b2y"/><path class="v5dw27x6u"/><path class="kamdbib6v"/><path class="v-q4myyjv"/><path class="n2ya_p02p"/><path class="h5yksf4iw"/><path class="e3fkgnlsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:home-desk-duotone-thin" /></template>
<style>
.e3fkgnlsf {
  d: path("M13 16h7");
}

.fdv44xbzc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 7v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h5yksf4iw {
  d: path("M13 12h7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ii4t72bxj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 7h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kamdbib6v {
  d: path("M2 7h20");
}

.n2ya_p02p {
  d: path("M13 7v13h7V7");
}

.qggih1b2y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v-q4myyjv {
  d: path("M4 7v13");
}

.v5dw27x6u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 16h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yb_89281i {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 7v13h7V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
