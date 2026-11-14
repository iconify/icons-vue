<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjlzmbcuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:air-quality-station" /></template>
<style>
.qjlzmbcuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h8v8H3Zm4 8v10.5m-3 0h6m4-17q1.75-1.5 3.5 0t3.5 0M14 9q1.75-1.5 3.5 0T21 9m-7 4.5q1.75-1.5 3.5 0t3.5 0");
}

</style>
