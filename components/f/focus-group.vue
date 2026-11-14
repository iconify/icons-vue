<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="crvixfblo"/><path class="e6s5jn_2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:focus-group" /></template>
<style>
.crvixfblo {
  d: path("M5.5 2.5h13A2.5 2.5 0 0 1 21 5v10a2.5 2.5 0 0 1-2.5 2.5h-8l-4 3.5v-3.5h-1A2.5 2.5 0 0 1 3 15V5a2.5 2.5 0 0 1 2.5-2.5Z");
}

.e6s5jn_2r {
  d: path("M10 7.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-2.25 7.25q0-2.5 4.25-2.5t4.25 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
