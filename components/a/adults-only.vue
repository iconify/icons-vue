<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="znva7pegk"/><path class="vfywzm5ev"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:adults-only" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vfywzm5ev {
  d: path("M9 8.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-1.5 9.25c0-2.25 2-3.5 4.5-3.5s4.5 1.25 4.5 3.5");
}

.znva7pegk {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Zm2.75-6.75l13.5 13.5");
}

</style>
