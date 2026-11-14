<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el6j8ebox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bone-density" /></template>
<style>
.el6j8ebox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 6.75h11C18 5 20 4.25 21 5.5c.75 1 .25 2.25-.75 3c1 .75 1.5 2 .75 3c-1 1.25-3 .5-3.5-1.25h-11C6 12 4 12.75 3 11.5c-.75-1-.25-2.25.75-3c-1-.75-1.5-2-.75-3C4 4.25 6 5 6.5 6.75ZM9 8.5h5.5m0 12a3.5 3.5 0 0 1 7 0m-7 0h7m-3.5 0l1.75-3");
}

</style>
