<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uty4b-b7c"/><path class="ppjc0mbvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:invoice-attachment" /></template>
<style>
.ppjc0mbvu {
  d: path("M14.25 12.5V4.75a2.75 2.75 0 0 1 5.5 0V15.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uty4b-b7c {
  d: path("M3.5 4H17v17.5H3.5ZM7 11h4.5M7 15h6");
}

</style>
