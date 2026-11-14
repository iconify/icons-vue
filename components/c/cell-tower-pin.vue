<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxq8rynmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cell-tower-pin" /></template>
<style>
.mxq8rynmx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11c-2-2-4-3.5-4-5a4 4 0 0 1 8 0c0 1.5-2 3-4 5ZM6.5 21.5L12 14l5.5 7.5m-8.75-3h6.5");
}

</style>
