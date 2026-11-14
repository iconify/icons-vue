<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hpsqe1b6i"/><path class="hv_b-1bzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:daypack" /></template>
<style>
.hpsqe1b6i {
  d: path("M7 6h10a2 2 0 0 1 2 2v11.5a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2Zm3.25 0V4.75a1.75 1.75 0 0 1 3.5 0V6");
}

.hv_b-1bzg {
  d: path("M7.5 13.5h9v5h-9Zm1.25-7v7m6.5-7v7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
