<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t7eay_aag"/><path class="ejkj6th1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calendar-shared" /></template>
<style>
.ejkj6th1k {
  d: path("M16.25 15.5h4.25v4.25");
}

.t7eay_aag {
  d: path("M11.1 21H3V4.5h17v7.6M3 9.5h17m-12.5-7v4m8-4v4M15 21l5.25-5.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
