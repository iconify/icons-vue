<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dtr1fi93a"/><path class="v6op74bzs"/><path class="fkzn23bsb"/><path class="kz0naab0d"/><path class="u4z3yfbwn"/><path class="kpspt_bpo"/><path class="sd8rzobni"/><path class="bcvts4b4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:load-shed-duotone-thin" /></template>
<style>
.bcvts4b4i {
  d: path("M13 18.5V21");
}

.dtr1fi93a {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 5v9h16V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fkzn23bsb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 17v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kpspt_bpo {
  d: path("M7 8h10");
}

.kz0naab0d {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 18.5V21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sd8rzobni {
  d: path("M17 17v2.5");
}

.u4z3yfbwn {
  d: path("M4 5v9h16V5");
}

.v6op74bzs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 8h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
