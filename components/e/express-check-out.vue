<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_h_fmbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:express-check-out" /></template>
<style>
.l_h_fmbgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.416 19.083L8.75 18.25l-3.75 2V3h14v8.7m-.65.55h-6.1v5.3M8.5 6.5h7m-7 3h7m4.25 5.25L16 18h4.25L17 21.5");
}

</style>
