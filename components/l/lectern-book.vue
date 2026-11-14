<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io3pe5rmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lectern-book" /></template>
<style>
.io3pe5rmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5c3-1 6-.75 8.5 1c2.5-1.75 5.5-2 8.5-1v4.75c-3-1-6-.75-8.5.75c-2.5-1.5-5.5-1.75-8.5-.75ZM3 12.75h18L18.5 16h-13ZM12 16v5.5m-4.5 0h9M12 5.5V10");
}

</style>
