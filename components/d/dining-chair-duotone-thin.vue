<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y185wqbff"/><path class="h8f-l8mxz"/><path class="yyycpdbdg"/><path class="jakiyuxzs"/><path class="rrxc-4bqr"/><path class="ckxsheb0b"/><path class="z22xlf92i"/><path class="u3jess8hd"/><path class="o682nlgep"/><path class="r182r524c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dining-chair-duotone-thin" /></template>
<style>
.ckxsheb0b {
  d: path("M7 3v10h10V3");
}

.h8f-l8mxz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 16h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jakiyuxzs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 16v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o682nlgep {
  d: path("M17 16v5");
}

.r182r524c {
  d: path("M7 9h10");
}

.rrxc-4bqr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 9h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u3jess8hd {
  d: path("M7 16v5");
}

.y185wqbff {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3v10h10V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yyycpdbdg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 16v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z22xlf92i {
  d: path("M5 16h14");
}

</style>
