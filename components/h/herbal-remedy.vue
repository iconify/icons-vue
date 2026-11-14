<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_in2ub7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:herbal-remedy" /></template>
<style>
.p_in2ub7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h18c0 5.5-4 8.5-9 8.5s-9-3-9-8.5Zm11.5 2.5l5-9.5m-13 4.5C6.5 5 9 3 13 3c0 3.5-2.5 5.5-6.5 5.5Z");
}

</style>
