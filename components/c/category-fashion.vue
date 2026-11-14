<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knwfo7bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-fashion" /></template>
<style>
.knwfo7bmd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 6l-8 5l2.5 3l2-1.5v8h7v-8l2 1.5l2.5-3zM9.5 4c0-1.25 2.5-1.25 2.5.5");
}

</style>
