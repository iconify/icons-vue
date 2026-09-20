<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nnzlfsekh"/><path class="teszqoqtj"/><path class="zqsgc7abe"/><path class="x1_r36phd"/><path class="lpz1dcbuc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chargeback-outline-regular" /></template>
<style>
.lpz1dcbuc {
  d: path("M11.5 9.5 9 12l2.5 2.5");
}

.nnzlfsekh {
  d: path("M2 8a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.teszqoqtj {
  d: path("M5.5 10.5v3");
}

.x1_r36phd {
  d: path("M9 12h6");
}

.zqsgc7abe {
  d: path("M18.5 10.5v3");
}

</style>
