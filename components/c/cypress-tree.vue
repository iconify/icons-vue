<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_s76zbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cypress-tree" /></template>
<style>
.y_s76zbzj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c1.5 2 2.5 3.5 2.25 5c1.25 2 1.75 4 1.5 5.5c.75 2 .75 4.5-1.25 5.5h-5c-2-1-2-3.5-1.25-5.5c-.25-1.5.25-3.5 1.5-5.5c-.25-1.5.75-3 2.25-5Zm0 16v3m-4 0h8");
}

</style>
