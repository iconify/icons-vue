<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="frpdz9bxu"/><path class="md-w8io9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lightbulb" /></template>
<style>
.frpdz9bxu {
  d: path("M9.5 15a6.5 6.5 0 1 1 5 0v2.5h-5Zm.75 5.5h3.5");
}

.md-w8io9k {
  d: path("m10 11.5l2 2l2-2m-2 2V15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
