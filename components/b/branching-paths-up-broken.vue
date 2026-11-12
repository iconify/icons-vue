<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wrqhnubdm"/><path class="c6g87kbzs"/><path class="n7bi59bvp"/><path class="f0le29xkr"/><path class="si_mtzbvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:branching-paths-up-broken" /></template>
<style>
.c6g87kbzs {
  d: path("M16 8C13.7909 8 12 9.79086 12 12V18");
}

.f0le29xkr {
  d: path("M8 8C10.2091 8 12 9.79086 12 12V18");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n7bi59bvp {
  stroke-linejoin: round;
  d: path("M8 8H6M7.5 6.5L6 8L7.5 9.5");
}

.si_mtzbvj {
  d: path("M22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C21.5093 4.43821 21.8356 5.80655 21.9449 8");
}

.wrqhnubdm {
  stroke-linejoin: round;
  d: path("M16 8H18M16.5 6.5L18 8L16.5 9.5");
}

</style>
