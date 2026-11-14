<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a52o5io9u"/><path class="tp-ih275l"/><path class="tf2fi2b6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:core-sample" /></template>
<style>
.a52o5io9u {
  d: path("M6.5 4.5a5.5 2 0 1 0 11 0a5.5 2 0 1 0-11 0Z");
}

.tf2fi2b6x {
  d: path("M6.5 10.5q2.75-1.5 5.5 0t5.5 0m-11 5h11");
}

.tp-ih275l {
  d: path("M6.5 4.5v15a5.5 2 0 0 0 11 0v-15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
