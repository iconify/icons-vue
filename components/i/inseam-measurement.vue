<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rl14ns7at"/><path class="p_hpofbuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:inseam-measurement" /></template>
<style>
.p_hpofbuw {
  d: path("M12 16v5.5M11 17l1-1l1 1m-2 3.5l1 1l1-1");
}

.rl14ns7at {
  d: path("M7 2.5h10l4 19h-4.5L12 7.5l-4.5 14H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
