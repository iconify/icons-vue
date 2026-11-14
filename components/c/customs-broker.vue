<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c-0yi2b4q"/><path class="lghkniujf"/><path class="k-1gbdb0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:customs-broker" /></template>
<style>
.c-0yi2b4q {
  d: path("M11.5 18.5h-9v-13h17v5.6M8 5.5V3.75A1.25 1.25 0 0 1 9.25 2.5h3.5A1.25 1.25 0 0 1 14 3.75V5.5m-11.5 5h17");
}

.k-1gbdb0b {
  d: path("M16.25 17.75L17.5 19l2.25-2.25");
}

.lghkniujf {
  d: path("m18 13.5l3.75 1.5v3c0 2.25-1.75 3.5-3.75 4c-2-.5-3.75-1.75-3.75-4v-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
