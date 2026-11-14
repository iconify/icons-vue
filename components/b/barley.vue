<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbqe13qbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:barley" /></template>
<style>
.tbqe13qbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5V14M9 9a3 5 0 1 0 6 0a3 5 0 1 0-6 0Zm1-3.5l-4-3m8 3l4-3M9 9L4.5 6.5M15 9l4.5-2.5m-7.5 12c2.5-.5 4.5-2 5-4.5");
}

</style>
