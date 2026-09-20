<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o60er10sa"/><path class="tkmkigbtv"/><path class="jh_3rl5dl"/><path class="nm-w_pb4m"/><path class="g1x6u_bif"/><path class="uw5kuce7r"/><path class="czysiurpc"/><path class="yg08zkbcc"/><path class="ah-zd_bma"/><path class="i699y-pkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:jet-bridge-duotone-thin" /></template>
<style>
.ah-zd_bma {
  d: path("M13 9v7");
}

.czysiurpc {
  d: path("M3 9h15v7H3");
}

.g1x6u_bif {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 6v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i699y-pkg {
  d: path("M21 6v13");
}

.jh_3rl5dl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nm-w_pb4m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o60er10sa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tkmkigbtv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 9h15v7H3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uw5kuce7r {
  d: path("M3 3v18");
}

.yg08zkbcc {
  d: path("M8 9v7");
}

</style>
