<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6vd8nlcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-crusher" /></template>
<style>
.m6vd8nlcu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.75h19M4.5 17v-2.25l3.5-1l1.5-1.25h5l1.5 1.25l3.5 1V17Zm-2 3h19M12 3.5V7M9.75 4.75L12 7l2.25-2.25");
}

</style>
