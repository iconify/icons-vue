<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6bp5ohwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anti-collision-beacon" /></template>
<style>
.v6bp5ohwo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 16v-4a4 4 0 0 1 8 0v4Zm-2.5 0h13v3.5h-13ZM12 2.5v2m-7 1L6.5 7M19 5.5L17.5 7m-15 5h2m15 0h2");
}

</style>
