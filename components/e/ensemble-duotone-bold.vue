<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="u_1mgzb6f"/><path class="nipy3h_db"/><path class="lydrxfslk"/><path class="tv_y06bgj"/><path class="liucm7_ra"/><path class="uxl9_oo-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ensemble-duotone-bold" /></template>
<style>
.liucm7_ra {
  d: path("m7 13 3 3 -3 3 -3 -3Z");
}

.lydrxfslk {
  fill: currentColor;
  d: path("m17 13 3 3 -3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nipy3h_db {
  fill: currentColor;
  d: path("m7 13 3 3 -3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tv_y06bgj {
  d: path("m12 3 3 3 -3 3 -3 -3Z");
}

.u_1mgzb6f {
  fill: currentColor;
  d: path("m12 3 3 3 -3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.uxl9_oo-x {
  d: path("m17 13 3 3 -3 3 -3 -3Z");
}

</style>
