<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="plq5es14y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:globular-cluster" /></template>
<style>
.plq5es14y {
  d: path("M10.5 7.25q.75 2.5 3.25 3.25q-2.5.75-3.25 3.25q-.75-2.5-3.25-3.25q2.5-.75 3.25-3.25ZM15 13q.5 1.75 2.25 2.25q-1.75.5-2.25 2.25q-.5-1.75-2.25-2.25Q14.5 14.75 15 13Zm1.25-4.75h.01M8.25 16h.01M13 5h.01");
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
