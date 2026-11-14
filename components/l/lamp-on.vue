<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g17uynb_x"/><path class="t55dmlbcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lamp-on" /></template>
<style>
.g17uynb_x {
  fill: currentColor;
  d: path("M7.75 7.5h8.5L19 14H5Z");
}

.t55dmlbcw {
  d: path("M12 14v7m-3.5 0h7M12 2v2.5m-6.5-.75L7 5m11.5-1.25L17 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
