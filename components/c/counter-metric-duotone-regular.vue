<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="akt7bbyym"/><path class="f2oriqw8z"/><path class="ozvla0_ac"/><path class="lwf2z_aas"/><path class="iulb4mb6k"/><path class="hwmj2eixw"/><path class="m0wo8tb6s"/><path class="ulyohmb5e"/><path class="u7sb4-hdn"/><path class="oifr9zbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:counter-metric-duotone-regular" /></template>
<style>
.akt7bbyym {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 8.5v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f2oriqw8z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4.5 9 7 6.5 9.5 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hwmj2eixw {
  d: path("M7 8.5v9");
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lwf2z_aas {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14.5 13 2.5 2.5 2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m0wo8tb6s {
  d: path("M4.5 9 7 6.5 9.5 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.ozvla0_ac {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 6.5v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u7sb4-hdn {
  d: path("m14.5 13 2.5 2.5 2.5 -2.5");
}

.ulyohmb5e {
  d: path("M17 6.5v9");
}

</style>
