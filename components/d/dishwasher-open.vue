<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="blvwpmb4u"/><path class="qjp3ou2ni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dishwasher-open" /></template>
<style>
.blvwpmb4u {
  d: path("M4 2.5h16V16H4ZM4 16h16l1.5 5.5h-19ZM4 6h16");
}

.qjp3ou2ni {
  d: path("M8 16a4 4 0 0 1 8 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
