<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="atayijbjq"/><path class="kuy4hgzke"/><path class="uk1-9vbiz"/><path class="ps2g__eqt"/><path class="w_izoda_u"/><path class="xy4qp4foh"/><path class="ymbpusb5b"/><path class="epou1mbuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dog-duotone-bold" /></template>
<style>
.atayijbjq {
  fill: currentColor;
  d: path("M7 6c1 -1 3 -1 5 -1s4 0 5 1c0.5 2 0.5 5 0 7 0 4 -2 6 -5 6s-5 -2 -5 -6c-0.5 -2 -0.5 -5 0 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.epou1mbuy {
  d: path("M11 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.kuy4hgzke {
  fill: currentColor;
  d: path("M7 7c-1.5 0 -2.5 2 -2.5 5 0 2 1 3 2.5 2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ps2g__eqt {
  fill: currentColor;
  d: path("M11 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uk1-9vbiz {
  fill: currentColor;
  d: path("M17 7c1.5 0 2.5 2 2.5 5 0 2 -1 3 -2.5 2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.w_izoda_u {
  d: path("M7 6c1 -1 3 -1 5 -1s4 0 5 1c0.5 2 0.5 5 0 7 0 4 -2 6 -5 6s-5 -2 -5 -6c-0.5 -2 -0.5 -5 0 -7");
}

.xy4qp4foh {
  d: path("M7 7c-1.5 0 -2.5 2 -2.5 5 0 2 1 3 2.5 2Z");
}

.ymbpusb5b {
  d: path("M17 7c1.5 0 2.5 2 2.5 5 0 2 -1 3 -2.5 2Z");
}

</style>
