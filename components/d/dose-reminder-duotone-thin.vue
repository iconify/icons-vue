<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iij8_24og"/><path class="lgsfugb0a"/><path class="rruu58b-y"/><path class="u6dphkbyx"/><path class="k1uyapbnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dose-reminder-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iij8_24og {
  fill: currentColor;
  d: path("m4 11 5 -5a3.5 3.5 0 0 1 5 5l-5 5a3.5 3.5 0 0 1 -5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.k1uyapbnn {
  d: path("M17 14v3h3");
}

.lgsfugb0a {
  fill: currentColor;
  d: path("M13 17a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rruu58b-y {
  d: path("m4 11 5 -5a3.5 3.5 0 0 1 5 5l-5 5a3.5 3.5 0 0 1 -5 -5");
}

.u6dphkbyx {
  d: path("M13 17a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
