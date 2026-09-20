<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m1sxkkbgc"/><path class="itcs4-8rc"/><path class="hvzqqmbfz"/><path class="racwnfbjp"/><path class="p33iqc74e"/><path class="et-iwmblh"/><path class="nqnw98byf"/><path class="f0qz9mbvk"/><path class="t3iybibvf"/><path class="wbz8a-gmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bed-duotone-bold" /></template>
<style>
.et-iwmblh {
  d: path("M2 18v-7h20v7");
}

.f0qz9mbvk {
  d: path("M4 11V7h6v4");
}

.hvzqqmbfz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 11V7h6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.itcs4-8rc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 14h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m1sxkkbgc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 18v-7h20v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nqnw98byf {
  d: path("M2 14h20");
}

.p33iqc74e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 18v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.racwnfbjp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t3iybibvf {
  d: path("M3 18v2.5");
}

.wbz8a-gmi {
  d: path("M21 18v2.5");
}

</style>
