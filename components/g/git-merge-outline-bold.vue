<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kn0tcm93r"/><path class="jg5k_rbda"/><path class="qp__wx2fk"/><path class="dhp6n31qa"/><path class="gjb6r-bki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:git-merge-outline-bold" /></template>
<style>
.dhp6n31qa {
  d: path("M6 7.5V12l4.5 4.5");
}

.gjb6r-bki {
  d: path("M18 7.5V12l-4.5 4.5");
}

.jg5k_rbda {
  d: path("M16 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.kn0tcm93r {
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.qp__wx2fk {
  d: path("M10 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
