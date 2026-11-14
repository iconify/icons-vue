<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rnszyfbvu"/><path class="b5q2itb1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:handheld-console-retro" /></template>
<style>
.b5q2itb1l {
  d: path("M7.75 5h8.5v6.5h-8.5ZM9 14.25v3.5M7.25 16h3.5m4.5-1.75h.01M13.5 16.5h.01");
}

.rnszyfbvu {
  d: path("M7 2.5h10a2 2 0 0 1 2 2v12a5 5 0 0 1-5 5H7a2 2 0 0 1-2-2v-15a2 2 0 0 1 2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
