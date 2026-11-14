<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i-ljidj3m"/><path class="q28tpvetz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:entry-ramp-right" /></template>
<style>
.i-ljidj3m {
  d: path("M7 21.5v-19M7 17c0-6 5-9 10-9");
}

.q28tpvetz {
  d: path("M14.25 5.25L17 8l-2.75 2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
