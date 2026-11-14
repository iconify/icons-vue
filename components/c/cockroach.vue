<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i2golpbow"/><path class="y4nzvbb2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cockroach" /></template>
<style>
.i2golpbow {
  d: path("M8.5 14a3.5 6.5 0 1 0 7 0a3.5 6.5 0 1 0-7 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y4nzvbb2a {
  d: path("M11 7.75C10.5 5 8 3 5.5 2.5M13 7.75C13.5 5 16 3 18.5 2.5m-9.25 8l-3.75-2m3 5.5H4m5.25 3.5L5.5 20m9.25-9.5l3.75-2m-3 5.5H20m-5.25 3.5L18.5 20");
}

</style>
