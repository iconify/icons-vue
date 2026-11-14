<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7pfj2upt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hockey-shoulder-pads" /></template>
<style>
.v7pfj2upt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 3.5h-2L7 6v10l3.5 4.5Zm3 0h2L17 6v10l-3.5 4.5ZM7 6q-4 0-4 6h4m10-6q4 0 4 6h-4");
}

</style>
