<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sou16vbyo"/><path class="dyiy7hbmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:all-off" /></template>
<style>
.dyiy7hbmg {
  d: path("M9 19.5v-5h4m3 1a3.5 3.5 0 1 0 4 0m-2-1.25v3.25");
}

.sou16vbyo {
  d: path("M11.772 19.5H2.5v-9L11 3l8.5 7.5v.928");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
