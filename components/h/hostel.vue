<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4p7-yzjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hostel" /></template>
<style>
.k4p7-yzjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5v19m18-19v19M3 9.5h18M3 17h18M5.5 6.25h4V9.5h-4Zm0 7.5h4V17h-4ZM17 9.5v12m0-8.25h4M17 20h4");
}

</style>
