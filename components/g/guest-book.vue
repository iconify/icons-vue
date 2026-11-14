<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aycxrmbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:guest-book" /></template>
<style>
.aycxrmbwp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21.5 11.598V4c-4-.5-7.25 0-9.5 1.5C9.75 4 6.5 3.5 2.5 4v13.5c4-.5 7.25 0 9.5 1.5q.297-.198.617-.373M12 5.5V19m3 2l.5-2.5L20 14l1.25 1.25l-4.5 4.5Z");
}

</style>
