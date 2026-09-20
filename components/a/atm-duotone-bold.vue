<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qdrw7hb2a"/><path class="n-868jblo"/><path class="fm1j79plm"/><path class="og4-69b6c"/><path class="rv8gzbbzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:atm-duotone-bold" /></template>
<style>
.fm1j79plm {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.n-868jblo {
  fill: currentColor;
  d: path("M7 5h10v5H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.og4-69b6c {
  d: path("M7 5h10v5H7Z");
}

.qdrw7hb2a {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rv8gzbbzr {
  d: path("M9 18v4h6v-4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
