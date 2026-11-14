<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwbkj8boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:function" /></template>
<style>
.cwbkj8boi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 4c-1-1-2.25-1.25-3.25-.75S11.25 4.75 11 6L9 18c-.25 1.25-.75 2.25-1.75 2.75S5 21 4 20M7.5 9.5h6M16.75 8c-2.5 3-2.5 10 0 13m2.5-13c2.5 3 2.5 10 0 13");
}

</style>
