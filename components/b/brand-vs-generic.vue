<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xldy3eb3t"/><path class="fg8f0yjjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brand-vs-generic" /></template>
<style>
.fg8f0yjjj {
  d: path("m7.117 10.494l.019.038a1.5 1.5 0 0 0 1.129.82l.041.006a.41.41 0 0 1 .227.699l-.029.029a1.5 1.5 0 0 0-.432 1.328l.007.04a.41.41 0 0 1-.594.432l-.037-.019a1.5 1.5 0 0 0-1.396 0l-.037.019a.41.41 0 0 1-.594-.432l.007-.04a1.5 1.5 0 0 0-.432-1.328l-.029-.029a.41.41 0 0 1 .227-.699l.041-.006a1.5 1.5 0 0 0 1.129-.82l.019-.038a.41.41 0 0 1 .734 0M13 12h8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xldy3eb3t {
  d: path("M2.5 12a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0M13 12a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0");
}

</style>
