<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b-pphqpeq"/><path class="sfnyx4wnk"/><path class="numygebfx"/><path class="xelgb6ber"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:container-network-outline-bold" /></template>
<style>
.b-pphqpeq {
  d: path("M3 8a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.numygebfx {
  d: path("M10 12.5a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sfnyx4wnk {
  d: path("M6 6v14");
}

.xelgb6ber {
  d: path("M10 12.5h7");
}

</style>
