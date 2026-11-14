<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j-egtfbpv"/><path class="ie87xklmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:colour-wheel-half" /></template>
<style>
.ie87xklmx {
  d: path("M9 16.75a3 3 0 0 1 6 0m-.75-2.25l4.5-4.5M12 13.75v-6.5M9.75 14.5L5.25 10");
}

.j-egtfbpv {
  d: path("M2.5 16.75a9.5 9.5 0 0 1 19 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
