<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jwy3ciu5d"/><path class="dp4kxqa2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fabric-roll" /></template>
<style>
.dp4kxqa2h {
  d: path("M9 16.5h11a1.5 1.5 0 0 1 1.5 1.5v2.5M7 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.jwy3ciu5d {
  d: path("M2.5 10a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
