<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5kmpwfqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gantt-bars-sharp" /></template>
<style>
.j5kmpwfqt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75v18.5M5.5 3.75h8v3.5h-8zm4 6.5h9v3.5h-9zm3.75 6.5h8v3.5h-8z");
}

</style>
