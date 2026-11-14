<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0duf92vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ao-dai" /></template>
<style>
.o0duf92vo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4.25L7.5 5l-4 9.5h2l3-6l1 4.5l-1 8.5h7l-1-8.5l1-4.5l3 6h2l-4-9.5l-2.5-.75Zm0-1.75h4v1.75h-4ZM9.5 13l-4 8m9-8l4 8");
}

</style>
