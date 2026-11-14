<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wrcg6qhaf"/><path class="mnb1ubb5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heat-recovery-unit" /></template>
<style>
.mnb1ubb5a {
  d: path("m6 15l12-6m-2.75-1L18 9l-1 2.75M18 15l-3.5-1.75m-5-2.5L6 9m2.75-1L6 9l1 2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wrcg6qhaf {
  d: path("M2.5 4.5h19v15h-19Z");
}

</style>
