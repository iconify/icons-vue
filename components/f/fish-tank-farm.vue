<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="cppyiwbyk"/><path class="tx5h6mbvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fish-tank-farm" /></template>
<style>
.cppyiwbyk {
  d: path("M7.757 16.243a6 6 0 0 1 0-8.486m8.486 0a6 6 0 0 1 0 8.486");
}

.tx5h6mbvm {
  d: path("M7.5 12c1.5-2.25 4.5-2.25 6 0l2-1.75v3.5l-2-1.75c-1.5 2.25-4.5 2.25-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdgu3ybil {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
