<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mft8ztshw"/><path class="n_5sjmbib"/><path class="t_57glb-y"/><path class="imu-axb_c"/><path class="yvotc3bin"/><path class="m1k1s7nte"/><path class="mi_m6achy"/><path class="l_9_psbce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ingress-traffic-duotone-bold" /></template>
<style>
.imu-axb_c {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l_9_psbce {
  d: path("M21 6v12");
}

.m1k1s7nte {
  d: path("M10 12h10");
}

.mft8ztshw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 3H3v18h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mi_m6achy {
  d: path("m17 9 3 3 -3 3");
}

.n_5sjmbib {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t_57glb-y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yvotc3bin {
  d: path("M8 3H3v18h5");
}

</style>
