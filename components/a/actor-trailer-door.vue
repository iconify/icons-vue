<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mr64643cv"/><path class="dwz3wx9ns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:actor-trailer-door" /></template>
<style>
.dwz3wx9ns {
  d: path("M13 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-5.5-2V7.5H11V16M7.5 7.5L5 9v8.5L7.5 16");
}

.mr64643cv {
  d: path("M2.5 4h16v12h-16Zm16 9.5h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
