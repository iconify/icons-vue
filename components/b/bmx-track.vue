<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gd620bjvp"/><path class="safmdkbkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bmx-track" /></template>
<style>
.gd620bjvp {
  d: path("M4.5 11a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm9 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.safmdkbkl {
  d: path("M7.5 11h4l-2-4m-1 0h2m1 4l3-4.5l2 4.5m-2-4.5l-.75-2h1.5M2.5 20.5c4 0 6-3.75 9.5-3.75s5.5 3.75 9.5 3.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
