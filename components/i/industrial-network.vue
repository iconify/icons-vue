<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6p41fbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:industrial-network" /></template>
<style>
.p6p41fbae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5h19m-16.75 0V12M12 7.5V12m7.25-4.5V12M2.5 12H7v4.5H2.5Zm7.25 0h4.5v4.5h-4.5ZM17 12h4.5v4.5H17Z");
}

</style>
