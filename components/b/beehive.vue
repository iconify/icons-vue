<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_hqg1one"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beehive" /></template>
<style>
.g_hqg1one {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7L12 2.5L20.5 7Zm2 0h13v4.5h-13Zm-1 4.5h15V16h-15Zm1 4.5h13v4.5h-13ZM3 20.5h18m-10.25-2.25h2.5");
}

</style>
