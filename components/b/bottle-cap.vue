<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j1u9ro78p"/><path class="jh--vwb6r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bottle-cap" /></template>
<style>
.j1u9ro78p {
  d: path("m12 2.5l1.23 1.342l1.57-.92l.78 1.645l1.772-.416l.259 1.801l1.816.125l-.282 1.798l1.698.654l-.8 1.635l1.43 1.126l-1.246 1.327l1.035 1.497l-1.582.9l.547 1.736l-1.777.394l.012 1.82l-1.815-.148l-.525 1.743l-1.69-.676l-1.016 1.511L12 20.25l-1.416 1.144l-1.016-1.511l-1.69.676l-.525-1.743l-1.815.148l.012-1.82l-1.777-.394l.547-1.736l-1.582-.9l1.035-1.497l-1.246-1.327l1.43-1.126l-.8-1.635l1.698-.654l-.282-1.798l1.816-.125l.259-1.801l1.772.416l.78-1.645l1.57.92Z");
}

.jh--vwb6r {
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
