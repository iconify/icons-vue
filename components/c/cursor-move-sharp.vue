<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz1k4e3fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cursor-move-sharp" /></template>
<style>
.hz1k4e3fp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 2.75v12.5M2.75 9h12.5m-8.5-4L9 2.75L11.25 5m-4.5 8L9 15.25L11.25 13M5 6.75L2.75 9L5 11.25m8-4.5L15.25 9L13 11.25m1.68 3.06l5.89 2.63l.68.31l-.71.25l-2.08.75l-.71.25l-.31.68l-.63 1.39l-.31.68l-.24-.71l-2.02-5.83L14 14z");
}

</style>
