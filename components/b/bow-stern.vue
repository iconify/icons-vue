<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx9xwnbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bow-stern" /></template>
<style>
.sx9xwnbva {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 6h15M7 3.5L4.5 6L7 8.5m10-5L19.5 6L17 8.5M2.75 12h13.5c2.5 0 4.25.75 5 2.25l-2.6 4.35a1.75 1.75 0 0 1-1.5.9H5.5a1.75 1.75 0 0 1-1.65-1.17Zm1 3.25h16.5");
}

</style>
