<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1kevpbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-uniforms-workwear" /></template>
<style>
.g1kevpbhr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 2.5L12 13l3.25-10.5H18c.5 4 3 5.5 3 8.5v9a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1v-9c0-3 2.5-4.5 3-8.5ZM12 13v8M6.25 11v7m11.5-7v7");
}

</style>
