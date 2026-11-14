<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hlzpxe_kj"/><path class="uwqms7bvg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eye-heart" /></template>
<style>
.hlzpxe_kj {
  d: path("M2.5 9.75C4 6.5 6.6 4.5 9.75 4.5s5.75 2 7.25 5.25C15.5 13 12.9 15 9.75 15S4 13 2.5 9.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uwqms7bvg {
  d: path("M7.25 9.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM18 21s-3-1.9-3-4c0-1.1.8-2 1.75-2c.55 0 1 .25 1.25.75c.25-.5.7-.75 1.25-.75c.95 0 1.75.9 1.75 2c0 2.1-3 4-3 4Z");
}

</style>
