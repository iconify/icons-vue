<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jzln5b9mk"/><path class="pmeincb2n"/><path class="q2fp4ccin"/><path class="hh49znbxn"/><path class="w-wacblka"/><path class="xz1gkzbgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:group-tour-outline-bold" /></template>
<style>
.hh49znbxn {
  d: path("M3 19a4 4 0 0 1 8 0");
}

.jzln5b9mk {
  d: path("M4 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.pmeincb2n {
  d: path("M9.5 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.q2fp4ccin {
  d: path("M15 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w-wacblka {
  d: path("M8.5 19a4 4 0 0 1 8 0");
}

.xz1gkzbgx {
  d: path("M14 19a4 4 0 0 1 8 0");
}

</style>
