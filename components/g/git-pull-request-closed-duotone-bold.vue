<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qecovn3xi"/><path class="jz0b4rbqp"/><path class="h55f46bdv"/><path class="k10f39bdw"/><path class="i9t0t_bxf"/><path class="urzb4gbtk"/><path class="kn0tcm93r"/><path class="k5nz3bcao"/><path class="fg8libqda"/><path class="jgg5ctbbh"/><path class="kk_08-buh"/><path class="qn318hakm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:git-pull-request-closed-duotone-bold" /></template>
<style>
.fg8libqda {
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.h55f46bdv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 7.5v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i9t0t_bxf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m20.5 16.5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jgg5ctbbh {
  d: path("m15.5 16.5 5 5");
}

.jz0b4rbqp {
  fill: currentColor;
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.k10f39bdw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15.5 16.5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k5nz3bcao {
  d: path("M6 7.5v9");
}

.kk_08-buh {
  d: path("m20.5 16.5 -5 5");
}

.kn0tcm93r {
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.qecovn3xi {
  fill: currentColor;
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qn318hakm {
  d: path("M18 14V9h-6L9 6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.urzb4gbtk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 14V9h-6L9 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
