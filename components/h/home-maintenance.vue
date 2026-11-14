<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8e209b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-maintenance" /></template>
<style>
.c8e209b6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.044 20.5H3.5v-10L12 3.25l8.5 7.25v.456M18.75 14a2.5 2.5 0 1 0 2.75 2.75m-4.25 1.5L14.5 21");
}

</style>
