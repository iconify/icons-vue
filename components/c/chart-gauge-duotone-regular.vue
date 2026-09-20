<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="emyboub8n"/><path class="qqcycfb_y"/><path class="p753cdl8a"/><path class="wmvbnibcr"/><path class="ng35sb6yg"/><path class="u4c9tcc0l"/><path class="t50oj1u1o"/><path class="eyettubom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-gauge-duotone-regular" /></template>
<style>
.emyboub8n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eyettubom {
  d: path("M18.5 16H21");
}

.ng35sb6yg {
  d: path("M3 16a9 9 0 0 1 18 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p753cdl8a {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qqcycfb_y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 16 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t50oj1u1o {
  d: path("M3 16h2.5");
}

.u4c9tcc0l {
  d: path("m12 16 5 -5");
}

.wmvbnibcr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18.5 16H21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
