<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m1veb4byo"/><path class="h3_q0ab1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:glue-gun-sharp" /></template>
<style>
.h3_q0ab1f {
  d: path("m17.09 6.6l3.32.95l.34.1v.7l-.34.1l-3.32.95l-.34.1v-3zM14 11.5v3.25");
}

.m1veb4byo {
  d: path("M2.75 8H7m8.5-3.5H7v7h1l-.13 1.49l-.49 5.52L7.25 20l1.41.5l.68.25l1.41.5l.15-1.49l.7-6.77l.15-1.49H17v-7z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
