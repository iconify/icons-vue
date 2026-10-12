<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yt_4_pnkq"/><path class="j6-ofzb8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chessboard" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6-ofzb8x {
  d: path("M6.75 6.75h1.5v1.5h-1.5zm6 0h1.5v1.5h-1.5zm-3 3h1.5v1.5h-1.5zm6 0h1.5v1.5h-1.5zm-9 3h1.5v1.5h-1.5zm6 0h1.5v1.5h-1.5zm-3 3h1.5v1.5h-1.5zm6 0h1.5v1.5h-1.5z");
}

.yt_4_pnkq {
  d: path("M4.5 3h15A1.5 1.5 0 0 1 21 4.5v15a1.5 1.5 0 0 1-1.5 1.5h-15A1.5 1.5 0 0 1 3 19.5v-15A1.5 1.5 0 0 1 4.5 3");
}

</style>
