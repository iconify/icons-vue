<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hi2_i-t_x"/><path class="a4ntl3b-i"/><path class="rcb4z6b_d"/><path class="m2_htfbkw"/><path class="xrw775b-m"/><path class="xpjur0b_h"/><path class="m2vc0klek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:key-lookup-duotone-thin" /></template>
<style>
.a4ntl3b-i {
  fill: currentColor;
  d: path("M10 9.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hi2_i-t_x {
  fill: currentColor;
  d: path("M5 11a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
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

.m2_htfbkw {
  d: path("m17 16 4 4");
}

.m2vc0klek {
  d: path("M12 12.5h2.5");
}

.rcb4z6b_d {
  d: path("M5 11a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

.xpjur0b_h {
  d: path("M12 11.5V14");
}

.xrw775b-m {
  d: path("M10 9.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
