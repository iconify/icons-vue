<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_lqzrfck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:axle-bar" /></template>
<style>
.y_lqzrfck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6H6v12H2.5ZM18 6h3.5v12H18ZM6 12h2.75m6.5 0H18m-9.25-2h6.5v4h-6.5Z");
}

</style>
