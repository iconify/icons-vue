<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tzwc64bwq"/><path class="a28wo5bxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:doppler-scan" /></template>
<style>
.a28wo5bxn {
  d: path("M6.804 7a6 6 0 0 1 10.392 0");
}

.tzwc64bwq {
  d: path("M2.5 11.5h19m-19 9h19M6 16h11m-2-2l2 2l-2 2M9.402 8.5a3 3 0 0 1 5.196 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
