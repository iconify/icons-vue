<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijdj1zboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:landmark-sharp" /></template>
<style>
.ijdj1zboj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.24 6.21l1.02 3.08q.24.71.53 1.4l1.17 2.87q.29.69.7 1.32l3.68 5.74l.41.63h-4l-.53-.53l-2.69-2.69l-.53-.53l-.53.53l-2.69 2.69l-.53.53h-4l.41-.63l3.68-5.74q.41-.63.7-1.32l1.17-2.87q.29-.69.53-1.4l1.02-3.08l.24-.71zM8 14.25h8M9.75 10h4.5M12 5.5V2.75");
}

</style>
