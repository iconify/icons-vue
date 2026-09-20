<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vti-hsydx"/><path class="oofqbbcku"/><path class="aqw9dybrd"/><path class="rs3qt4avn"/><path class="qq2o6m5os"/><path class="cx8rytfxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:house-chimney-duotone-regular" /></template>
<style>
.aqw9dybrd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 8h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cx8rytfxu {
  d: path("M13 8h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oofqbbcku {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 14V5h6v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qq2o6m5os {
  d: path("M13 14V5h6v16");
}

.rs3qt4avn {
  d: path("m2 21 7 -7 7 7");
}

.vti-hsydx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m2 21 7 -7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
