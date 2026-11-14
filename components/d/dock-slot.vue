<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q9dcoub0a"/><path class="llutszbko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dock-slot" /></template>
<style>
.llutszbko {
  d: path("M15.75 6.5h3v12h-3ZM8 13h.01");
}

.q9dcoub0a {
  d: path("M13 2.5h8.5v19H13Zm0 12.75a5.5 5.5 0 1 1 0-4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
