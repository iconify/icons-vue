<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wkdxs5b7w"/><path class="woeos_2de"/><path class="lgwvtrh-h"/><path class="jzeve79sx"/><path class="hdoh9g9pr"/><path class="z43nfgbva"/><path class="e030h51ix"/><path class="pn-mm5bcv"/><path class="ymw3aibdo"/><path class="tla8vyn6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cherry-pick-duotone-thin" /></template>
<style>
.e030h51ix {
  d: path("M10 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hdoh9g9pr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jzeve79sx {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lgwvtrh-h {
  fill: currentColor;
  d: path("M17 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pn-mm5bcv {
  d: path("M17 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.tla8vyn6c {
  d: path("M12 7v8");
}

.wkdxs5b7w {
  fill: currentColor;
  d: path("M3 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.woeos_2de {
  fill: currentColor;
  d: path("M10 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ymw3aibdo {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.z43nfgbva {
  d: path("M3 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
