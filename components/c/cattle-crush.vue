<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u28nmsb_r"/><path class="ofmm63kii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cattle-crush" /></template>
<style>
.ofmm63kii {
  d: path("M8.25 6.75Q6.75 6 7 3m8.75 3.75Q17.25 6 17 3m-6.75 8h.01m3.49 0h.01");
}

.u28nmsb_r {
  d: path("M4 2.5v19m16-19v19M7.5 7.5c0-1.5 9-1.5 9 0l-1 9c0 3.5-7 3.5-7 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
