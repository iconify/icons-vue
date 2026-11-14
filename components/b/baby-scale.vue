<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy45sxb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-scale" /></template>
<style>
.fy45sxb5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15h18v6.5H3Zm-.5-8.5c0 4 4 5.75 9.5 5.75s9.5-1.75 9.5-5.75M12 12.25V15m-2 3.25h4");
}

</style>
