<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz7w_9i8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:launch-abort" /></template>
<style>
.iz7w_9i8a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.5c2.25 1.75 3 4.25 3 7V16h-6V9.5c0-2.75.75-5.25 3-7Zm-3 8L3 13v2l2.5-1m6-3.5L14 13v2l-2.5-1m-3 4.75v2.75m7.5-2.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm.75-2l4 4");
}

</style>
