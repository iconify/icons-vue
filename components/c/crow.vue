<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="dnpy1wugi"/><path class="i56mfvb2o"/><path class="q6icwma0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crow" /></template>
<style>
.dnpy1wugi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 6.25c0-1 .75-1.75 1.75-1.75h1c1.5 0 2.5 1 2.75 2.5c3 1 5.25 3.25 6.25 5.75l1.7 2.6c.25.35.2.85-.15 1.1l-.75.55c-.3.2-.7.2-.95-.05l-2.6-1.45c-1.25.9-2.75 1.5-4.5 1.5c-3 0-5.25-2-5.25-4.75c0-1.75.5-3 1.25-4.25c-.35-.45-.5-1.1-.5-1.75");
}

.i56mfvb2o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.6 5.6L3.25 7.15c-.45.15-.45.75 0 .9L7.5 9.1Zm3.15 11.3l-.5 4.35H9m4.5-4.5l.5 4.5h1.25");
}

.q6icwma0c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 6.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
