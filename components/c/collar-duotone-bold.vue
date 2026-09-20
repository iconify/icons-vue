<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pzx9fiuzq"/><path class="xr_5e9b5a"/><path class="wqteuxb0p"/><path class="bo9_g-q3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:collar-duotone-bold" /></template>
<style>
.bo9_g-q3m {
  d: path("M10 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.pzx9fiuzq {
  fill: currentColor;
  d: path("M10 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.wqteuxb0p {
  d: path("M3 6c0 6 4 9 9 9s9 -3 9 -9");
}

.xr_5e9b5a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6c0 6 4 9 9 9s9 -3 9 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
