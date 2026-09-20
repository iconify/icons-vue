<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nk1mt_brr"/><path class="ra07l749q"/><path class="zawirs49s"/><path class="itq_ntb3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:letterbox-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.itq_ntb3g {
  d: path("M11 16v5");
}

.nk1mt_brr {
  fill: currentColor;
  d: path("M5 16v-6a6 6 0 0 1 12 0v6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ra07l749q {
  d: path("M5 16v-6a6 6 0 0 1 12 0v6Z");
}

.zawirs49s {
  d: path("M8 11h6");
}

</style>
