<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vnz4sfj5q"/><path class="vj06a7bup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:archive-restore" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vj06a7bup {
  d: path("m9.5 14l2.5-2.5l2.5 2.5");
}

.vnz4sfj5q {
  d: path("M4.25 3.5h15.5a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 19.75 8H4.25A1.75 1.75 0 0 1 2.5 6.25v-1A1.75 1.75 0 0 1 4.25 3.5M4 8v11a2.5 2.5 0 0 0 2.5 2.5h11A2.5 2.5 0 0 0 20 19V8m-8 10.5v-7");
}

</style>
