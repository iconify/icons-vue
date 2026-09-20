<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q8pkiebhf"/><path class="c26uqybpm"/><path class="y7d97_qtf"/><path class="cf2pd_8sh"/><path class="asjt_p6in"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:escrow-account-duotone-regular" /></template>
<style>
.asjt_p6in {
  d: path("M10.5 15a1.5 1.5 0 0 1 3 0");
}

.c26uqybpm {
  fill: currentColor;
  d: path("M9 15h6v3H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.cf2pd_8sh {
  d: path("M9 15h6v3H9Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q8pkiebhf {
  fill: currentColor;
  d: path("M9.5 4h5v2.5L18 10a7 7 0 1 1 -12 0l3.5 -3.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y7d97_qtf {
  d: path("M9.5 4h5v2.5L18 10a7 7 0 1 1 -12 0l3.5 -3.5Z");
}

</style>
