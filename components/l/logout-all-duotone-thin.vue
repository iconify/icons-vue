<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="czo2s0b0e"/><path class="nmwy4lp5x"/><path class="jibzvrd0i"/><path class="d556dgb1h"/><path class="x46tn-bjt"/><path class="wt76_hbmn"/><path class="l9cf9bbmd"/><path class="plqv1xi7k"/><path class="j_z-vb9qy"/><path class="xvmft_b5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:logout-all-duotone-thin" /></template>
<style>
.czo2s0b0e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 3H3v18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d556dgb1h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 15h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j_z-vb9qy {
  d: path("M10 15h10");
}

.jibzvrd0i {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17.5 6.5 20 9l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l9cf9bbmd {
  d: path("M10 9h10");
}

.nmwy4lp5x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 9h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.plqv1xi7k {
  d: path("M17.5 6.5 20 9l-2.5 2.5");
}

.wt76_hbmn {
  d: path("M9 3H3v18h6");
}

.x46tn-bjt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17.5 12.5 20 15l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xvmft_b5k {
  d: path("M17.5 12.5 20 15l-2.5 2.5");
}

</style>
