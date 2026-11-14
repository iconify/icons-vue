<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q5q4_bbdl"/><path class="sbc28bbuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-user" /></template>
<style>
.q5q4_bbdl {
  d: path("m4 10.5l8-7l8 7V20H4Z");
}

.sbc28bbuk {
  d: path("M10.5 11.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM9 18c.25-1.5 1.5-2.5 3-2.5s2.75 1 3 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
