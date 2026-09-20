<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ia5e4hb1l"/><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="ox90s7sqj"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="lx_qbigic"/><path class="atq4odb0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:baseline-metric-duotone-thin" /></template>
<style>
.atq4odb0h {
  d: path("M11 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.gms_xv68n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ia5e4hb1l {
  fill: currentColor;
  d: path("M11 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lx_qbigic {
  d: path("M7 14h12");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.ox90s7sqj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
