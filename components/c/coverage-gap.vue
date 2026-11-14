<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0_-g9beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coverage-gap" /></template>
<style>
.b0_-g9beb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 19.5h.01m-3.26-3.25q.227-.237.486-.439q.259-.201.544-.363t.592-.281q.306-.118.625-.191M6.25 12.5q.635-.528 1.356-.931m7.18-.703q.812.264 1.56.676q.747.413 1.404.958m-7.695-6.418q.559-.081 1.122-.116q.563-.034 1.127-.021q.564.012 1.124.072t1.115.166t1.097.258q.544.153 1.072.349q.529.197 1.039.438q.51.24.999.522M3.5 3.5l17 17");
}

</style>
