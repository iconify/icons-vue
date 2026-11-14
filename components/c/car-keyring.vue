<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h4zpqmzuy"/><path class="uo_sp7b3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-keyring" /></template>
<style>
.h4zpqmzuy {
  d: path("M10.25 10h6a1 1 0 0 1 1 1v9.5a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1V11a1 1 0 0 1 1-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uo_sp7b3t {
  d: path("M6.75 6.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm6.5 7.5h.01m-.01 3.5h.01");
}

</style>
