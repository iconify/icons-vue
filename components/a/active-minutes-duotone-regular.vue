<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xgscl2bdj"/><path class="mypzt1bhf"/><path class="lrge8gh-h"/><path class="y8piwob-e"/><path class="m6trofguq"/><path class="zirb-hbnv"/><path class="n0hr0gbrt"/><path class="y0y0ccsoe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:active-minutes-duotone-regular" /></template>
<style>
.lrge8gh-h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 21a9 9 0 1 1 9 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m6trofguq {
  d: path("M12 21a9 9 0 1 1 9 -9");
}

.mypzt1bhf {
  fill: currentColor;
  d: path("M14 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n0hr0gbrt {
  d: path("M14 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xgscl2bdj {
  fill: currentColor;
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y0y0ccsoe {
  d: path("M10 12h4");
}

.y8piwob-e {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zirb-hbnv {
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
