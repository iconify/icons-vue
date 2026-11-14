<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ept0mpmgh"/><path class="v4yaoovpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chives" /></template>
<style>
.ept0mpmgh {
  d: path("M5 3.5L9 16v5.5m3-19v19M17 8l-2 8v5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v4yaoovpi {
  d: path("M15.25 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM7.5 16h9");
}

</style>
