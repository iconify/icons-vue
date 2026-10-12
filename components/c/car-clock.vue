<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="y9tr6bcfx"><g mask="url(#SVGsZ1vtcCp)"><path class="mbf2pm3_i"/><path class="zbm7pqbjy"/></g><circle class="jhfl8tb7m"/><path class="sv_tli4wr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-clock" /></template>
<style>
.jf0axzbmx {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

.jhfl8tb7m {
  cx: 17.5px;
  cy: 17.5px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mbf2pm3_i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12.5L5.6 7.1a2 2 0 0 1 1.9-1.35h9a2 2 0 0 1 1.9 1.35l1.85 5.4v4.75a1 1 0 0 1-1 1H4.75a1 1 0 0 1-1-1Zm2.75 5.75v2.5m11-2.5v2.5m-13.25-9.5h15.5");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sv_tli4wr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 15.75v1.75l1.25 1");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zbm7pqbjy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 14.75h.01");
}

</style>
