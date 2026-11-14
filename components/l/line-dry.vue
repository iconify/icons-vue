<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oq2nkbb8e"/><path class="wv80v0bbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:line-dry" /></template>
<style>
.oq2nkbb8e {
  d: path("M3 20.5v-17h18v17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wv80v0bbg {
  d: path("M9.5 3.5L5.75 5.75L7 9.25l1.5-.5v8.75h7V8.75l1.5.5l1.25-3.5L14.5 3.5q-2.5 2.5-5 0Z");
}

</style>
