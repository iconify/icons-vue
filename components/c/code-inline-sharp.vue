<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="e408uacwa"/><path class="xc8hoccpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:code-inline-sharp" /></template>
<style>
.e408uacwa {
  d: path("M2.75 6.25h18.5v11.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xc8hoccpi {
  d: path("M9 9.5L6.75 12L9 14.5m6-5l2.25 2.5L15 14.5M11.25 12h1.5");
}

</style>
