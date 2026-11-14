<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lb-gg4eot"/><path class="agmyo8pgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baggage-tractor" /></template>
<style>
.agmyo8pgi {
  d: path("M4.5 17a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm11 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.lb-gg4eot {
  d: path("M13.5 15V9.5h3l1-4H20l1.5 4V15Zm-11 0h11m-10-7H11v7H3.5Zm2.25 0V5.5h3V8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
