<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tomofebck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:curling-takeout" /></template>
<style>
.tomofebck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h8v5h-8ZM5 14v-2.5h4m4.5 2.5h8v5h-8Zm2.5 0v-2.5h4M13 6h7.5m-2.25-2.25L20.5 6l-2.25 2.25");
}

</style>
