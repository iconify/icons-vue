<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdwv7t5cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cricketer-batting" /></template>
<style>
.xdwv7t5cc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-3 15.5C2.5 17 5 13 8.5 13s6 4 6 8.5m-1.232-9.33l3.464-2l5 8.66l-3.464 2ZM15 11.25L13.5 8.5");
}

</style>
