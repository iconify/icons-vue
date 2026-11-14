<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no_2fvb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:floating-solar" /></template>
<style>
.no_2fvb3d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3h14l-4 9.5H3ZM5 7.75h14M14 3l-4 9.5m-7 4q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0m-18 4q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
