<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c4e1y7wvc"/><path class="h36909btm"/><path class="rzbbkyb0w"/><path class="a76nyxbck"/><path class="l0v-b4kbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:circuit-close-outline-regular" /></template>
<style>
.a76nyxbck {
  d: path("M18 14v5");
}

.c4e1y7wvc {
  d: path("M4 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.h36909btm {
  d: path("M16 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rzbbkyb0w {
  d: path("M6 5v5");
}

</style>
