<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tyw98lblh"/><path class="toscoiuso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ev-charging-station" /></template>
<style>
.toscoiuso {
  d: path("m10 5.5l-2.5 5h3l-2.5 5");
}

.tyw98lblh {
  d: path("M4 2.5h10v19H4ZM14 8h2q1.5 0 1.5 1.5v7q0 2 1.75 2t1.75-2V7l-1.5-1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
