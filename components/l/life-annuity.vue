<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xu3nmbclo"/><path class="sf1ijidwf"/><path class="oj0aovi6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:life-annuity" /></template>
<style>
.oj0aovi6j {
  d: path("M8.25 9v6a3.75 1.75 0 0 0 7.5 0V9m-7.5 3a3.75 1.75 0 0 0 7.5 0");
}

.sf1ijidwf {
  d: path("M5 3.25L7.5 4l-.75 2.5M8.25 9a3.75 1.75 0 1 0 7.5 0a3.75 1.75 0 1 0-7.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xu3nmbclo {
  d: path("M16.5 4a9.25 9.25 0 1 1-9 0");
}

</style>
