<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="phu67w_rf"/><path class="wlci694hy"/><path class="w9co6ubnn"/><path class="rx7so7bjn"/><path class="pgjxgc_-z"/><path class="zugrvnb7t"/><path class="e325robmt"/><path class="bfcwd7bcm"/><path class="v7ifz5bvw"/><path class="leijmjbkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:buffet-duotone-bold" /></template>
<style>
.bfcwd7bcm {
  d: path("M13 13a4 4 0 0 1 8 0");
}

.e325robmt {
  d: path("M3 13a4 4 0 0 1 8 0");
}

.leijmjbkg {
  d: path("M18 13v6");
}

.pgjxgc_-z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.phu67w_rf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 13h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rx7so7bjn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v7ifz5bvw {
  d: path("M6 13v6");
}

.w9co6ubnn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 13a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wlci694hy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 13a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zugrvnb7t {
  d: path("M2 13h20");
}

</style>
