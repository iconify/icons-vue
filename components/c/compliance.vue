<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akzf2nj4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:compliance" /></template>
<style>
.akzf2nj4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4.5v16m-4.5 0h9M4.5 7h15m-17 6.5l2-6.5l2 6.5m-4 0c0 2 4 2 4 0m11 0l2-6.5l2 6.5m-4 0c0 2 4 2 4 0");
}

</style>
