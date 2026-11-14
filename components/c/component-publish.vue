<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd7au1bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:component-publish" /></template>
<style>
.kd7au1bqv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.186 13.814L10.5 18.5l-8-8l8-8l8 8l-1.687 1.687M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
