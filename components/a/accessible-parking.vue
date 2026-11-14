<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dkag5ac0u"/><path class="yu1r-pdvb"/><path class="f1bbb0bma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:accessible-parking" /></template>
<style>
.dkag5ac0u {
  d: path("M3 3h18v18H3Zm8 4h.01");
}

.f1bbb0bma {
  d: path("M10.5 11.25a3.5 3.5 0 1 1-3.5 3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yu1r-pdvb {
  d: path("M11 9.75v4.5h3.75l1.75 3.5");
}

</style>
