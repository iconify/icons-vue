<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phpxrjbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dish-alignment" /></template>
<style>
.phpxrjbgg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 6.25a6 6 0 0 0 8.5 8.5ZM10 16.5v5m-4 0h8.5m-.5 0a4 4 0 0 0-1.25-2.75M12.5 8l2-2m2-2L18 2.5");
}

</style>
