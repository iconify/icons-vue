<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r-26nac3w"/><path class="eord7ibqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:house-leaf" /></template>
<style>
.eord7ibqx {
  d: path("M15.25 20.75c0-4.25 1.75-6 5.75-6c0 4-1.5 6-5.75 6Zm-.5.75l3-3.25");
}

.r-26nac3w {
  d: path("M11.844 20.5H3.5v-10L12 3.25l8.5 7.25v1.456");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
