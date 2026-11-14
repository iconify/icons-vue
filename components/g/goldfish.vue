<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ecr4yb0fm"/><path class="t3xmgm3ui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:goldfish" /></template>
<style>
.ecr4yb0fm {
  d: path("M3.5 13c0-4 3-6 6.5-6c3 0 5.5 2 6.5 4.5l4.5-4q-1.5 5.5 0 11l-4.5-4C15.5 17 13 19 10 19c-3.5 0-6.5-2-6.5-6Z");
}

.t3xmgm3ui {
  d: path("M7.5 7.5c1-2.5 4-3.25 6 .25M7 11.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
