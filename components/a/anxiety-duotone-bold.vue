<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="iy0zj-beq"/><path class="izv17rqcw"/><path class="pdx7buv0t"/><path class="oordrjbbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:anxiety-duotone-bold" /></template>
<style>
.iy0zj-beq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 21v-4c-2 -2 -3 -5 -3 -8a7 7 0 0 1 14 -1c0 2 2 3 2 4s-1 1 -2 1v3a2 2 0 0 1 -2 2h-3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.izv17rqcw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 6 3 3 -3 3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oordrjbbh {
  d: path("m7 6 3 3 -3 3 3 3");
}

.pdx7buv0t {
  d: path("M6 21v-4c-2 -2 -3 -5 -3 -8a7 7 0 0 1 14 -1c0 2 2 3 2 4s-1 1 -2 1v3a2 2 0 0 1 -2 2h-3v3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
