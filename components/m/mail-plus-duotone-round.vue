<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rno51dg_c"/><path class="hf43g5bqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-plus-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hf43g5bqt {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 13v2a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h4M4 7l3 3c.64.64 1.72 1 3 1h3m2-5h6m-3-3v6");
}

.rno51dg_c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M22 15a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20H7a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5h4a.998.998 0 0 1 .99 1.141a6 6 0 0 0 .25 2.779c.52 1.556 1.603 2.735 3.003 3.551c1.093.638 2.364 1.031 3.638.985a4.8 4.8 0 0 0 1.725-.375A.997.997 0 0 1 22 13Z");
}

</style>
