<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ozzb4qbps"/><path class="dhqnqfb6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cast-net" /></template>
<style>
.dhqnqfb6x {
  d: path("M6.75 13.5q5.25 2 10.5 0M12 2.5v1");
}

.ozzb4qbps {
  d: path("M12 3.5L4 19q8 3 16 0Zm0 0L9.25 20M12 3.5L14.75 20");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
