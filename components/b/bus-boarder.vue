<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j615f7m9d"/><path class="mchtrnmjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bus-boarder" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j615f7m9d {
  d: path("M2.5 16V6a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v10Zm0-6.5h13");
}

.mchtrnmjc {
  d: path("M4 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0m6 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m9.75-5H20a1.5 1.5 0 0 1 1.5 1.5v5A1.5 1.5 0 0 1 20 21h-.25a1.5 1.5 0 0 1-1.5-1.5v-5a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
