<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hg_qa-8dv"/><path class="d8nxbmbei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:caravan-dealer" /></template>
<style>
.d8nxbmbei {
  d: path("M5.5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m9.5-12l6.5 3v11M7 8.5h1A1.5 1.5 0 0 1 9.5 10A1.5 1.5 0 0 1 8 11.5H7A1.5 1.5 0 0 1 5.5 10A1.5 1.5 0 0 1 7 8.5");
}

.hg_qa-8dv {
  d: path("M2.5 16.5V8A2.5 2.5 0 0 1 5 5.5h7.5A2.5 2.5 0 0 1 15 8v8.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
