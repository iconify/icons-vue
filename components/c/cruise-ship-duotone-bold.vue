<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jh-r4db2e"/><path class="r0ugme01d"/><path class="j2rh_abzz"/><path class="lo13e1bkv"/><path class="x212dunwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cruise-ship-duotone-bold" /></template>
<style>
.j2rh_abzz {
  d: path("M5 15v-4h14v4");
}

.jh-r4db2e {
  fill: currentColor;
  d: path("M2 15h20l-5 5H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lo13e1bkv {
  d: path("M9 11V7h7v4");
}

.r0ugme01d {
  d: path("M2 15h20l-5 5H7Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x212dunwb {
  d: path("M11 7V3h3v4");
}

</style>
