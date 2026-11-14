<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zedbf8byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lawn-weeds" /></template>
<style>
.zedbf8byr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 6.5L14.5 8l-.5 2l-2-.75l-2 .75l-.5-2L8 6.5L9.5 5l.5-2l2 .75L14 3l.5 2Zm-4 2.75V20.5m0-1Q6 19 5 14q4.5 1 7 5.5m0 0q6-.5 7-5.5q-4.5 1-7 5.5m-9 1h18");
}

</style>
