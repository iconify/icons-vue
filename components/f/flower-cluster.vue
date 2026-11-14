<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tfifdnbrb"/><path class="cxce6obus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flower-cluster" /></template>
<style>
.cxce6obus {
  d: path("M12 8.5v13m-6.5-6Q5.5 19 12 19m6.5-3.5q0 3.5-6.5 3.5");
}

.tfifdnbrb {
  d: path("M10.5 4a1.5 1.5 0 0 1 3 0a1.5 1.5 0 0 1 0 3a1.5 1.5 0 0 1-3 0a1.5 1.5 0 0 1 0-3ZM4 11a1.5 1.5 0 0 1 3 0a1.5 1.5 0 0 1 0 3a1.5 1.5 0 0 1-3 0a1.5 1.5 0 0 1 0-3Zm13 0a1.5 1.5 0 0 1 3 0a1.5 1.5 0 0 1 0 3a1.5 1.5 0 0 1-3 0a1.5 1.5 0 0 1 0-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
