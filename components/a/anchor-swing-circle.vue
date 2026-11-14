<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p44l8e18y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anchor-swing-circle" /></template>
<style>
.p44l8e18y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 6.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM12 8.25V18.5m-2.5-7.25h5M7.5 14a4.5 4.5 0 0 0 9 0m5-.5a9.5 9.5 0 0 1-1.75 4m-2.25 2.25a9.5 9.5 0 0 1-4 1.75m-3 0a9.5 9.5 0 0 1-4-1.75M4.25 17.5a9.5 9.5 0 0 1-1.75-4m0-3a9.5 9.5 0 0 1 1.75-4M6.5 4.25a9.5 9.5 0 0 1 4-1.75m3 0a9.5 9.5 0 0 1 4 1.75m2.25 2.25a9.5 9.5 0 0 1 1.75 4");
}

</style>
