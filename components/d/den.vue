<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mlhqxpbrs"/><path class="eg9sy5n4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:den" /></template>
<style>
.eg9sy5n4o {
  d: path("M8.5 18.5v-3a3.5 3.5 0 0 1 7 0v3");
}

.mlhqxpbrs {
  d: path("M2.5 18.5C4 8.5 9 5.5 12 5.5s8 3 9.5 13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
