<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tomkkdm-q"/><path class="g51arpxbx"/><path class="zemft8bom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cesspit-emptying" /></template>
<style>
.g51arpxbx {
  d: path("M5.5 15.5h16v-4l-3-3h-1.25v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tomkkdm-q {
  d: path("M9 4.5h1.5a4 4 0 0 1 4 4a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4a4 4 0 0 1 4-4");
}

.zemft8bom {
  d: path("M7 17.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m9 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-11-9H4A1.5 1.5 0 0 0 2.5 10v10");
}

</style>
