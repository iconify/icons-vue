<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwbzd7b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:apron-bus" /></template>
<style>
.gwbzd7b9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.1 18.5H3.5v-16h15v9.2M7 18.5V21M3.5 11h15M7 15h.01M15 15h.01m2.99-.5v7m-3-2.25l3-2l3 2m-4.5 2.25h3");
}

</style>
