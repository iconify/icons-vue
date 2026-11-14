<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2_-gd0qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:insulation-thermal" /></template>
<style>
.a2_-gd0qi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 2.5h7v19h-7Zm3.5 0v19M2.5 7Q4.25 5.5 6 7t3.5 0m-7 5q1.75-1.5 3.5 0t3.5 0m-7 5q1.75-1.5 3.5 0t3.5 0");
}

</style>
