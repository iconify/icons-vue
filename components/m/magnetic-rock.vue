<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzi47d-3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:magnetic-rock" /></template>
<style>
.kzi47d-3d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 16.5l1-7l4-3l3.75 2V15L7 18ZM14 7h3a5 5 0 0 1 0 10h-3v-3.25h3a1.75 1.75 0 0 0 0-3.5h-3Zm-8.25 7l2.75-3.5");
}

</style>
