<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct6zgubjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fiber-closure" /></template>
<style>
.ct6zgubjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 13.5v-3a5.5 5.5 0 0 1 11 0v3m-13 0h15V17h-15Zm-2 6c0-3 1-4.25 2-4.25m17 4.25c0-3-1-4.25-2-4.25");
}

</style>
