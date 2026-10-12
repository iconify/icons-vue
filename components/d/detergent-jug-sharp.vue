<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xl5vrybdt"/><path class="hroqw1bmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:detergent-jug-sharp" /></template>
<style>
.hroqw1bmm {
  d: path("M13.75 9.25h2.5v4.5h-2.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xl5vrybdt {
  d: path("M4.75 19.25V8.75l1.41-1.41l.18-.18l1.41-1.41h11.5v15.5H4.75zm3.5-16.5h4.5v3h-4.5z");
}

</style>
