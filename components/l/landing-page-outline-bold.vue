<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="viv5gg8xx"/><path class="atoje4bsc"/><path class="ndyoa79lx"/><path class="jgc62lvnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:landing-page-outline-bold" /></template>
<style>
.atoje4bsc {
  d: path("M2 6h20");
}

.jgc62lvnr {
  d: path("M9 10h7l-2 2 2 2H9");
}

.ndyoa79lx {
  d: path("M9 10v8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.viv5gg8xx {
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
