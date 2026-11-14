<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="ljf6hh7db"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eyewash-sign" /></template>
<style>
.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.ljf6hh7db {
  d: path("M6 8.25q6-4 12 0q-6 4-12 0Zm6 0h.01M12 13l1.25 1.75a1.75 1.75 0 1 1-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
