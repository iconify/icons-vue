<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ipb1x_bvt"/><path class="wno2bb6wt"/><path class="sscby3y4w"/><path class="mapwwf30m"/><path class="vqi6vft7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hazard-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ipb1x_bvt {
  fill: currentColor;
  d: path("m12 2.5 9.5 9.5 -9.5 9.5L2.5 12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mapwwf30m {
  d: path("M12 7v4.5");
}

.sscby3y4w {
  d: path("m12 2.5 9.5 9.5 -9.5 9.5L2.5 12Z");
}

.vqi6vft7m {
  d: path("M11 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.wno2bb6wt {
  fill: currentColor;
  d: path("M11 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
