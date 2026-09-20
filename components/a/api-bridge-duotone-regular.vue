<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h78mtnbkg"/><path class="amdyfrbnw"/><path class="u-kmlrghs"/><path class="fzmgr7bvw"/><path class="md3qg6xkk"/><path class="bvirm9d4j"/><path class="sxlwlmkmh"/><path class="n90p24bmq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:api-bridge-duotone-regular" /></template>
<style>
.amdyfrbnw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bvirm9d4j {
  d: path("M20 6v12");
}

.fzmgr7bvw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h78mtnbkg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.md3qg6xkk {
  d: path("M4 6v12");
}

.n90p24bmq {
  d: path("m10 10 2 2 -2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sxlwlmkmh {
  d: path("M4 12h16");
}

.u-kmlrghs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
