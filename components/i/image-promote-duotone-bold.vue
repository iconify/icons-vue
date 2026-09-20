<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j14g7qigh"/><path class="a8i34bcjs"/><path class="v1-fmxxhj"/><path class="h1cr44bva"/><path class="ts5ij9bsc"/><path class="hu1l55dbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:image-promote-duotone-bold" /></template>
<style>
.a8i34bcjs {
  fill: currentColor;
  d: path("M3 12a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.h1cr44bva {
  d: path("M3 12a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.hu1l55dbx {
  d: path("M9.5 15.5 12 13l2.5 2.5");
}

.j14g7qigh {
  fill: currentColor;
  d: path("M3 4.5A2.5 2.5 0 0 1 5.5 2h13A2.5 2.5 0 0 1 21 4.5 2.5 2.5 0 0 1 18.5 7h-13A2.5 2.5 0 0 1 3 4.5");
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

.ts5ij9bsc {
  d: path("M12 13v6");
}

.v1-fmxxhj {
  d: path("M3 4.5A2.5 2.5 0 0 1 5.5 2h13A2.5 2.5 0 0 1 21 4.5 2.5 2.5 0 0 1 18.5 7h-13A2.5 2.5 0 0 1 3 4.5");
}

</style>
