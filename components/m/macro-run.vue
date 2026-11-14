<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h94lg1-9d"/><path class="cqvy0ck9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:macro-run" /></template>
<style>
.cqvy0ck9r {
  d: path("M7 2.5h10a2 2 0 0 1 2 2V12m-5.5.5l8 4.5l-8 4.5Z");
}

.h94lg1-9d {
  d: path("M10.7 21.5H3V6h13v4.7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
