<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="e6o_mb6nf"/><path class="hu1e-ebii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:export-video-sharp" /></template>
<style>
.e6o_mb6nf {
  d: path("M2.75 7.75h13.5v13.5H2.75z");
}

.hu1e-ebii {
  d: path("m8.38 12.16l2.99 1.93l.63.41l-.63.41l-2.99 1.93l-.63.41v-5.5zm5.87-9.41h7v7m0-7l-7 7");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
