<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="saw47101n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:book-stack-x" /></template>
<style>
.saw47101n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4h13v6.5H5Zm9.1 14H2.5v-7.5H19v2.6M15 4v6.5m-9 0V18m9.5-2.5l5 5m0-5l-5 5");
}

</style>
