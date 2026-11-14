<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k6g95absz"/><path class="o6qniueau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flower-girl-dress" /></template>
<style>
.k6g95absz {
  d: path("M8.5 3q3.5 3 7 0q.25 3.75 2.25 5L17 11l3.5 10h-17L7 11l-.75-3q2-1.25 2.25-5Z");
}

.o6qniueau {
  d: path("M11.5 10.5a1 1 0 1 1 1 0a1 1 0 1 1 0 1a1 1 0 1 1-1 0a1 1 0 1 1 0-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
