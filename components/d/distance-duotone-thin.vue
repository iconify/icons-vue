<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ld7zhcybq"/><path class="cw9gc0jvg"/><path class="qp2-4lbll"/><path class="u_41jqbcx"/><path class="tvvl11btt"/><path class="veni6hbgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:distance-duotone-thin" /></template>
<style>
.cw9gc0jvg {
  fill: currentColor;
  d: path("M16 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ld7zhcybq {
  fill: currentColor;
  d: path("M4 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qp2-4lbll {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7.5 16.5 9 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tvvl11btt {
  d: path("m7.5 16.5 9 -9");
}

.u_41jqbcx {
  d: path("M4 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.veni6hbgn {
  d: path("M16 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
