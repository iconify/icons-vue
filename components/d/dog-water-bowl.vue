<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nu2z3kk2m"/><path class="ok3t0kbxa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-water-bowl" /></template>
<style>
.nu2z3kk2m {
  d: path("M5 12.5h14l2.5 8h-19Z");
}

.ok3t0kbxa {
  d: path("M7 16.5q2.5-1.5 5 0t5 0m-5-14S9.25 5.5 9.25 7a2.75 2.75 0 0 0 5.5 0c0-1.5-2.75-4.5-2.75-4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
