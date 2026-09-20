<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rr3cudbwc"/><path class="uhd6vogdz"/><path class="reyvph0yg"/><path class="ki-5h0s5c"/><path class="dgtjfobks"/><path class="ab_fsy82a"/><path class="p04-68bfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:license-scan-duotone-bold" /></template>
<style>
.ab_fsy82a {
  d: path("M8.5 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.dgtjfobks {
  d: path("M6 9.5h8");
}

.ki-5h0s5c {
  d: path("M6 6h12");
}

.p04-68bfh {
  d: path("m13.5 20 2 2");
}

.reyvph0yg {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.rr3cudbwc {
  fill: currentColor;
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
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

.uhd6vogdz {
  fill: currentColor;
  d: path("M8.5 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
