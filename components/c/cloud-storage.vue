<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z7vrhvb4d"/><path class="v3uytxxvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cloud-storage" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v3uytxxvt {
  d: path("M6.5 16v4a5.5 1.5 0 0 0 11 0v-4");
}

.z7vrhvb4d {
  d: path("M7 11.75h10a3 3 0 0 0 0-6a5 5 0 0 0-9.5.75a2.75 2.75 0 0 0-.5 5.25ZM6.5 16a5.5 1.5 0 1 0 11 0a5.5 1.5 0 1 0-11 0Z");
}

</style>
