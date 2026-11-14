<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t50_ifbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bell-tower-pagoda" /></template>
<style>
.t50_ifbpx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7q4-.5 7.5-4.5q3.5 4 7.5 4.5Zm-1 8.5q3-.5 3.75-2.25h9.5Q17.5 15 20.5 15.5m-18 5Q5.75 20 6.75 18h10.5q1 2 4.25 2.5M7.25 7v11m9.5-11v11M10 10.5c0-2 .75-3.5 2-3.5s2 1.5 2 3.5Z");
}

</style>
