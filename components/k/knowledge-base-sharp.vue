<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="psizqf3sa"/><path class="un4vwvb4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:knowledge-base-sharp" /></template>
<style>
.psizqf3sa {
  d: path("M4.75 2.75h14.5v18.5H4.75zm3.5 0v18.5");
}

.un4vwvb4o {
  d: path("M13.75 7.5q.42 3.08 3.5 3.5q-3.08.42-3.5 3.5q-.42-3.08-3.5-3.5q3.08-.42 3.5-3.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
