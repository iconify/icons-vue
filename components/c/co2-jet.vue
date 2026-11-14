<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d6vfi5b_h"/><path class="bvrvnub3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:co2-jet" /></template>
<style>
.bvrvnub3a {
  d: path("M14 9a2.25 2.25 0 0 1 0-4.5a2.75 2.75 0 0 1 5.25 0a2.25 2.25 0 0 1 0 4.5Z");
}

.d6vfi5b_h {
  d: path("M3.5 10h7v11.5h-7Zm2 0V6.75h6.25m-3.25 0V10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
