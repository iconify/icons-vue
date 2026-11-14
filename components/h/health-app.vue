<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l1tv0xafw"/><path class="yntwclbqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-app" /></template>
<style>
.l1tv0xafw {
  d: path("M6 2.5h12v19H6ZM10.5 5h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yntwclbqx {
  d: path("M8.5 13H10l1-2.5l1.75 5l1-2.5h1.75m-5 6h3");
}

</style>
