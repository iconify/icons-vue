<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c7e9jobtm"/><path class="m3vqp1bum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blister-pack-empty" /></template>
<style>
.c7e9jobtm {
  d: path("M5.5 2.5H17L20.5 6v13.5a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2v-15a2 2 0 0 1 2-2Z");
}

.m3vqp1bum {
  d: path("M6 8.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm7.5.5A2.25 2.25 0 1 0 18 9a2.25 2.25 0 1 0-4.5 0Zm-5.25 4.25a2.25 2.25 0 0 1 0 4.5m7.5-4.5a2.25 2.25 0 0 1 0 4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
