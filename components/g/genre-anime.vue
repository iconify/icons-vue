<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mur8w6bbb"/><path class="lwi4kzbsm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:genre-anime" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lwi4kzbsm {
  d: path("M6.25 12.75a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m6-1.5h.01M17 9.5l.5-2.5m1.25 3.75L20 8.5m.5 3.5l1.5-1.5");
}

.mur8w6bbb {
  d: path("M2.5 13q9.5-9.5 19 0q-9.5 8.5-19 0");
}

</style>
