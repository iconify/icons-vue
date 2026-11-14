<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j8c9j4bge"/><path class="llcfgp5zz"/><path class="lggw-7dmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lunch-allowance" /></template>
<style>
.j8c9j4bge {
  d: path("M10.908 21.5H3.5L5 5.5l1.25-2l1.25 2l1.25-2l1.25 2l1.25-2l1.25 2l1.25-2l1.25 2l.36 3.845M4.75 8.25h10.5");
}

.lggw-7dmn {
  d: path("M18 15.5c-.25-.5-.75-.75-1.25-.75c-.75 0-1.25.5-1.25 1c0 1.25 2.5.75 2.5 2c0 .5-.5 1-1.25 1s-1-.25-1.25-.75");
}

.llcfgp5zz {
  d: path("M7.25 8.25v10.5L3.75 21M12 16.75a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
