<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v23dk-htm"/><path class="xvl0zubxy"/><path class="ed6f0ubpi"/><path class="k85brnbpq"/><path class="h2sq3fbpa"/><path class="p0leisbvy"/><path class="xyj-l9cjp"/><path class="kex2cdcje"/><path class="r7dhdp-mq"/><path class="oq9ztqbxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:magic-trick-duotone-bold" /></template>
<style>
.ed6f0ubpi {
  fill: currentColor;
  d: path("M11 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.h2sq3fbpa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k85brnbpq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 18V9h10v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kex2cdcje {
  d: path("M18 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.oq9ztqbxu {
  d: path("M11 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.p0leisbvy {
  d: path("M7 18V9h10v9");
}

.r7dhdp-mq {
  d: path("M4 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v23dk-htm {
  fill: currentColor;
  d: path("M18 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xvl0zubxy {
  fill: currentColor;
  d: path("M4 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

</style>
