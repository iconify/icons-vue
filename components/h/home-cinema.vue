<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o87z4c_nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-cinema" /></template>
<style>
.o87z4c_nd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 9h14l-2 12.5H7Zm0 0c-.5-2.5 2-4 3.5-2.75c.5-2.5 4-3.25 5.25-1c1.5-1.5 4.5-.75 4.25 1.75c1.5.25 1.5 1.75 1 2M9.75 9l.5 12.5m4-12.5l-.5 12.5");
}

</style>
