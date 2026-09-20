<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pbz4y6llk"/><path class="xqz890wro"/><path class="ejtyvbbdg"/><path class="rkhcgsbdl"/><path class="t4vjq-bqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-combo-outline-bold" /></template>
<style>
.ejtyvbbdg {
  d: path("M17 15v4");
}

.pbz4y6llk {
  d: path("M5 13v6");
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t4vjq-bqk {
  d: path("m4 9 4 -4 4 4 4 -4 4 4");
}

.xqz890wro {
  d: path("M11 12v7");
}

</style>
