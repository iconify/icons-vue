<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="oqf3av09z"/><path class="cyel4trrt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:desk-calendar-sharp" /></template>
<style>
.cyel4trrt {
  d: path("M8.75 13.5h6.5V18h-6.5z");
}

.oqf3av09z {
  d: path("M8 4.25v2.5m4-2.5v2.5m4-2.5v2.5m-9.5 0H19l.18 1.49l1.39 11.52l.18 1.49H3.25l.18-1.49L4.82 8.24L5 6.75zm-2 3.75h15");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
