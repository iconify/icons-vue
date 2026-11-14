<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jfx06c9me"/><path class="sye78vbzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:door-lock" /></template>
<style>
.jfx06c9me {
  d: path("M5.5 21V4.5a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v7.75M2.5 21h9.75M15 11.5h.01M15 17h6v4.5h-6Z");
}

.sye78vbzq {
  d: path("M16.25 17v-1a1.75 1.75 0 0 1 3.5 0v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
