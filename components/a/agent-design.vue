<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4jjh0q1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:agent-design" /></template>
<style>
.d4jjh0q1o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.5q.75 6.75 7.5 7.5q-6.75.75-7.5 7.5q-.75-6.75-7.5-7.5q6.75-.75 7.5-7.5ZM15 21l.75-2.75l4-4l2 2l-4 4Zm.75-2.75l2 2");
}

</style>
