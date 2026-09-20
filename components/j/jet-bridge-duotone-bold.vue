<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qoibgxtiv"/><path class="vw7h_8lgs"/><path class="p949upesk"/><path class="e-o23pb7t"/><path class="dpo98j1ht"/><path class="uw5kuce7r"/><path class="czysiurpc"/><path class="yg08zkbcc"/><path class="ah-zd_bma"/><path class="i699y-pkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:jet-bridge-duotone-bold" /></template>
<style>
.ah-zd_bma {
  d: path("M13 9v7");
}

.czysiurpc {
  d: path("M3 9h15v7H3");
}

.dpo98j1ht {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 6v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e-o23pb7t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i699y-pkg {
  d: path("M21 6v13");
}

.p949upesk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qoibgxtiv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uw5kuce7r {
  d: path("M3 3v18");
}

.vw7h_8lgs {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 9h15v7H3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yg08zkbcc {
  d: path("M8 9v7");
}

</style>
