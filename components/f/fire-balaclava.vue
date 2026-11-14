<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="up-g2acgg"/><path class="mg8e5098m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fire-balaclava" /></template>
<style>
.mg8e5098m {
  d: path("M8.75 10a3.25 2.5 0 1 0 6.5 0a3.25 2.5 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.up-g2acgg {
  d: path("M12 2.5c4 0 6 3 6 7V13c0 2-1 3-2 3.5l4 1.5c1 .5 1.5 1.5 1.5 3.5h-19c0-2 .5-3 1.5-3.5l4-1.5C7 16 6 15 6 13V9.5c0-4 2-7 6-7Z");
}

</style>
