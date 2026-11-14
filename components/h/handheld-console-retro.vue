<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q593ytbdy"/><path class="dvqc81b-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:handheld-console-retro" /></template>
<style>
.dvqc81b-t {
  d: path("M9.25 5h5.5a1.5 1.5 0 0 1 1.5 1.5V10a1.5 1.5 0 0 1-1.5 1.5h-5.5a1.5 1.5 0 0 1-1.5-1.5V6.5A1.5 1.5 0 0 1 9.25 5M9 14.25v3.5M7.25 16h3.5m4.5-1.75h.01M13.5 16.5h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q593ytbdy {
  d: path("M7 2.5h10a2 2 0 0 1 2 2v12a5 5 0 0 1-5 5H7a2 2 0 0 1-2-2v-15a2 2 0 0 1 2-2");
}

</style>
