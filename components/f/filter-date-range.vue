<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y62xeyxoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:filter-date-range" /></template>
<style>
.y62xeyxoy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.732 19.366L8 17.5V11L2.5 3.5h15L12 11v1.499m2.5 2.751h7v6.25h-7Zm2-1.25v2.25m3-2.25v2.25m-5 1.75h7");
}

</style>
