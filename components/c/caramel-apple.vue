<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="azzhheshw"/><path class="k1_5qdbkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:caramel-apple" /></template>
<style>
.azzhheshw {
  d: path("M12 8c-2.5-1.5-7-1-7 5c0 5 3.5 8.5 5.5 8.5c.75 0 1-.5 1.5-.5s.75.5 1.5.5c2 0 5.5-3.5 5.5-8.5c0-6-4.5-6.5-7-5Zm0-5.5V8");
}

.k1_5qdbkt {
  d: path("M5 13c2 0 2.25 3 4 3s1.5-2.5 3-2.5s1.25 3 3 3s2-3.5 4-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
