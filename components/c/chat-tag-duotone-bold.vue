<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sqmravmye"/><path class="gudl2cg4z"/><path class="hbdbg_bcy"/><path class="lyjarcbwz"/><path class="xa3yjwu7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chat-tag-duotone-bold" /></template>
<style>
.gudl2cg4z {
  fill: currentColor;
  d: path("M8 8h5l3 3 -3 3H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hbdbg_bcy {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.lyjarcbwz {
  d: path("M7 18v3l3 -3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sqmravmye {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xa3yjwu7k {
  d: path("M8 8h5l3 3 -3 3H8Z");
}

</style>
