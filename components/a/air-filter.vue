<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="axzu7jl0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:air-filter" /></template>
<style>
.axzu7jl0q {
  d: path("m6.5 8l2.25-2L11 8l2.25-2l2.25 2l2.25-2M6.5 13l2.25-2L11 13l2.25-2l2.25 2l2.25-2M6.5 18l2.25-2L11 18l2.25-2l2.25 2l2.25-2");
}

.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
