<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_3t8rbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-art-supplies" /></template>
<style>
.x_3t8rbtf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5c-5 0-8.5 3.5-8.5 8c0 4 3 5.5 5 5s2 1.5 2 2.5c0 1.5 1 1.75 1.75 1.75c5.25 0 8.25-3.75 8.25-8.75S17 3.5 12 3.5ZM8 9h.01M12 7h.01M16 9h.01");
}

</style>
