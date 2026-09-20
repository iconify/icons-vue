<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zxrob3sge"/><path class="k-8kltbgj"/><path class="cpc3z_b1u"/><path class="wi1v9gbty"/><path class="rv-5y_bth"/><path class="dfcdzc65k"/><path class="kwx_mgnfk"/><path class="kdmnrabtq"/><path class="y4k_22w_l"/><path class="h_p-57bvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:crawl-duotone-thin" /></template>
<style>
.cpc3z_b1u {
  fill: currentColor;
  d: path("M17 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.dfcdzc65k {
  d: path("M3 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.h_p-57bvu {
  d: path("M19 8v8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-8kltbgj {
  fill: currentColor;
  d: path("M17 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kdmnrabtq {
  d: path("M17 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.kwx_mgnfk {
  d: path("M17 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.rv-5y_bth {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wi1v9gbty {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y4k_22w_l {
  d: path("M8 5h8");
}

.zxrob3sge {
  fill: currentColor;
  d: path("M3 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
