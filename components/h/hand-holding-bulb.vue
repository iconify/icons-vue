<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgzt9t01b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hand-holding-bulb" /></template>
<style>
.pgzt9t01b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 11c-1.5-1-2.5-2.5-2.5-4.5a4.5 4.5 0 0 1 9 0c0 2-1 3.5-2.5 4.5Zm-7.5 7h3l3 3.5h7l5-4.5c.75-.75 0-2-1-1.5l-3.75 3H11.5m-1.5-5h4M10.75 16h2.5");
}

</style>
