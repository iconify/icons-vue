<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5_3-zb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lamp-off" /></template>
<style>
.u5_3-zb9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.666 3.699L7.75 3.5h8.5L19 10h-5.042m-7.9 0H5l.328-.776M12 15.9V21m-3.5 0h7M3.5 3.5l17 17");
}

</style>
