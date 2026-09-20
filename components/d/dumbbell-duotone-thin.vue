<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cc0pq4b_o"/><path class="coabtnkvx"/><path class="jbk-w-tox"/><path class="rfy_enbzb"/><path class="g6sdhib4i"/><path class="vslz5yb3q"/><path class="xhm9ckc2y"/><path class="gl0vd86ea"/><path class="h26bvabki"/><path class="tmc4aacim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dumbbell-duotone-thin" /></template>
<style>
.cc0pq4b_o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.coabtnkvx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g6sdhib4i {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gl0vd86ea {
  d: path("M18 7v10");
}

.h26bvabki {
  d: path("M3 9v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jbk-w-tox {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rfy_enbzb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tmc4aacim {
  d: path("M21 9v6");
}

.vslz5yb3q {
  d: path("M6 12h12");
}

.xhm9ckc2y {
  d: path("M6 7v10");
}

</style>
