<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="laiyn8mjf"/><path class="f0a5_1dcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-profiling" /></template>
<style>
.f0a5_1dcz {
  fill: currentColor;
  d: path("M13 8V5h1.75v3Zm3.25 0V2.5H18V8Zm3 0V6H21v2Z");
}

.laiyn8mjf {
  d: path("M3 10.5h18v11H3Zm9 0v11m-9-7.25h18m-18 3.5h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
