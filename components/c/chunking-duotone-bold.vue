<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xzhm7354z"/><path class="ipn--e3af"/><path class="zzj8h_6-i"/><path class="z81xltbwu"/><path class="kmd_30j9x"/><path class="u0acwebrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chunking-duotone-bold" /></template>
<style>
.ipn--e3af {
  fill: currentColor;
  d: path("M2 17a3 3 0 0 1 3 -3h3a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kmd_30j9x {
  d: path("M2 17a3 3 0 0 1 3 -3h3a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u0acwebrq {
  d: path("M13 17a3 3 0 0 1 3 -3h3a3 3 0 0 1 3 3 3 3 0 0 1 -3 3h-3a3 3 0 0 1 -3 -3");
}

.xzhm7354z {
  fill: currentColor;
  d: path("M2 7a3 3 0 0 1 3 -3h14a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.z81xltbwu {
  d: path("M2 7a3 3 0 0 1 3 -3h14a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3");
}

.zzj8h_6-i {
  fill: currentColor;
  d: path("M13 17a3 3 0 0 1 3 -3h3a3 3 0 0 1 3 3 3 3 0 0 1 -3 3h-3a3 3 0 0 1 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
