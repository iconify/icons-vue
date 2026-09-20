<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yak845b1c"/><path class="qbodsccli"/><path class="l517yxbln"/><path class="tpq9gxgiu"/><path class="vy1nh429l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:copy-into-duotone-bold" /></template>
<style>
.l517yxbln {
  d: path("M12 9v6");
}

.qbodsccli {
  d: path("M6 4a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tpq9gxgiu {
  d: path("m8 11 4 4 4 -4");
}

.vy1nh429l {
  d: path("M3 16v5h18v-5");
}

.yak845b1c {
  fill: currentColor;
  d: path("M6 4a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
