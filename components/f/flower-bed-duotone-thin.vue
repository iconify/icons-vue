<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nizbrguot"/><path class="mypzt1bhf"/><path class="lgv7os48g"/><path class="j-ilx17of"/><path class="c6c2d6ciw"/><path class="o8od38cnm"/><path class="of_dlbc-j"/><path class="pma7fkjmg"/><path class="n0hr0gbrt"/><path class="gf_3phz1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flower-bed-duotone-thin" /></template>
<style>
.c6c2d6ciw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gf_3phz1c {
  d: path("M16 14v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-ilx17of {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 11v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lgv7os48g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mypzt1bhf {
  fill: currentColor;
  d: path("M14 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n0hr0gbrt {
  d: path("M14 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nizbrguot {
  fill: currentColor;
  d: path("M6 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o8od38cnm {
  d: path("M4 18h16");
}

.of_dlbc-j {
  d: path("M6 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.pma7fkjmg {
  d: path("M8 11v7");
}

</style>
