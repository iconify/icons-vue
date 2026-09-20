<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p33184bqk"/><path class="l_-i6ebvx"/><path class="qi-35ihhp"/><path class="f2w30qblw"/><path class="s-etibjpa"/><path class="ben7bq53u"/><path class="xr2p35g3w"/><path class="kr1cz4b8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:corner-radius-duotone-thin" /></template>
<style>
.ben7bq53u {
  d: path("M4 10a6 6 0 0 1 6 -6");
}

.f2w30qblw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 4h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kr1cz4b8j {
  d: path("M9 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.l_-i6ebvx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 10v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p33184bqk {
  fill: currentColor;
  d: path("M9 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qi-35ihhp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 10a6 6 0 0 1 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s-etibjpa {
  d: path("M4 10v10");
}

.xr2p35g3w {
  d: path("M10 4h10");
}

</style>
