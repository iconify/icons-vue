<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dktry7bqc"/><path class="d25ja-bje"/><path class="zmcli4b5c"/><path class="h8qtyvbna"/><path class="ebc_hc9-q"/><path class="bo51iypxr"/><path class="e771rwjjh"/><path class="xysie__pz"/><path class="se-pwqb_b"/><path class="km3h1bbzc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cyclone-duotone-regular" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.d25ja-bje {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 17A5 5 0 0 1 9 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dktry7bqc {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.e771rwjjh {
  d: path("M9 17A5 5 0 0 1 9 7");
}

.ebc_hc9-q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 19h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h8qtyvbna {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.km3h1bbzc {
  d: path("M15 19h7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.se-pwqb_b {
  d: path("M2 5h7");
}

.xysie__pz {
  d: path("M15 7a5 5 0 0 1 0 10");
}

.zmcli4b5c {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 7a5 5 0 0 1 0 10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
