<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dktry7bqc"/><path class="ykdlbqbze"/><path class="u5x5uhehv"/><path class="xq-gwrblx"/><path class="l1grp2orp"/><path class="l6e2wzbuh"/><path class="qtj-xccdg"/><path class="ne_b8wtyo"/><path class="fsv7g_bbj"/><path class="bo51iypxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:focus-duotone-bold" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dktry7bqc {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fsv7g_bbj {
  d: path("M9 21H3v-6");
}

.l1grp2orp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 21H3v-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l6e2wzbuh {
  d: path("M3 9V3h6");
}

.ne_b8wtyo {
  d: path("M21 15v6h-6");
}

.qtj-xccdg {
  d: path("M15 3h6v6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u5x5uhehv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 3h6v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xq-gwrblx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 15v6h-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ykdlbqbze {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 9V3h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
