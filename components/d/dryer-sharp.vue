<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="larn2wbwu"/><circle class="lvri69kam"/><path class="s2x1a7b3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dryer-sharp" /></template>
<style>
.larn2wbwu {
  d: path("M3.75 2.75h16.5v18.5H3.75zM10 5.5h4");
}

.lvri69kam {
  cx: 12px;
  cy: 13.75px;
  r: 5px;
}

.s2x1a7b3r {
  d: path("m10.4 11.75l-1.119 1l1.119 1l1.119 1l-1.119 1m3.2-4l-1.119 1l1.119 1l1.119 1l-1.119 1");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
