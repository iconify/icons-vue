<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t286_lbil"/><path class="or0ipgfuc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:food-truck-park" /></template>
<style>
.or0ipgfuc {
  d: path("M4.5 11.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3.25 4.25h7.75m-6 0l-1.25 5.75m5.5-5.75L21 21.5m-8-2.75h9");
}

.t286_lbil {
  d: path("M2.5 10V2.5h9L15 6v4Zm2.75-4.25h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
