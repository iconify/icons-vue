<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fx3gz59vk"/><path class="r_f4pfmky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:angler-casting" /></template>
<style>
.fx3gz59vk {
  d: path("M3.5 21C7 14 12 6.5 20 4.5m0 0c1 4 .5 7.5-1.5 10");
}

.r_f4pfmky {
  d: path("M16.75 17a1.75 2.5 0 1 0 3.5 0a1.75 2.5 0 1 0-3.5 0ZM5 15.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
