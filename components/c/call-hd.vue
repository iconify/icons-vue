<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qt6_1_bbd"/><path class="dfo5uo1zi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:call-hd" /></template>
<style>
.dfo5uo1zi {
  d: path("M13 2.5a8.5 8.5 0 0 1 8.5 8.5");
}

.qt6_1_bbd {
  d: path("M3 10.5C3 9 4 8 5.5 8h1.25l1.5 3.75L6.5 13c1 2.25 3.25 4.5 5.5 5.5l1.25-1.75l3.75 1.5v1.25c0 1.25-1 2-2.5 2c-6.5 0-11.5-5-11.5-11ZM13 8a3 3 0 0 1 3 3m-3-5.75A5.75 5.75 0 0 1 18.75 11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
