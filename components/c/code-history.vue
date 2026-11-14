<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ixvl08bxs"/><path class="f47hego-r"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-history" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.f47hego-r {
  d: path("M8 7L6 9.5L8 12m3-5l2 2.5l-2 2.5m3.75 6a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ixvl08bxs {
  d: path("M12 19H3V2.5h13v9.8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
