<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r761c-bxw"/><path class="m3bn7sb5q"/><path class="y-4o8e34g"/><path class="l7ynjsgwx"/><path class="wc595gblk"/><path class="aff9hemvj"/><path class="u36itk5tb"/><path class="m_erznomk"/><path class="tr__z6b9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:endangered-duotone-regular" /></template>
<style>
.aff9hemvj {
  d: path("M9 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.l7ynjsgwx {
  fill: currentColor;
  d: path("M18 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.m_erznomk {
  d: path("M19 6v8");
}

.m3bn7sb5q {
  fill: currentColor;
  d: path("M9 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r761c-bxw {
  fill: currentColor;
  d: path("M4 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tr__z6b9j {
  d: path("M18 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.u36itk5tb {
  d: path("M3 16a5 5 0 0 1 10 0 4 4 0 0 1 -5 4 4 4 0 0 1 -5 -4");
}

.wc595gblk {
  d: path("M4 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.y-4o8e34g {
  fill: currentColor;
  d: path("M3 16a5 5 0 0 1 10 0 4 4 0 0 1 -5 4 4 4 0 0 1 -5 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
