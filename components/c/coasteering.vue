<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5njdjbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coasteering" /></template>
<style>
.o5njdjbva {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h8L13 6.5L11.5 9l2 2.5h-11ZM3 15.5q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0M3 20.25q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
