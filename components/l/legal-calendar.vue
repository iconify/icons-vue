<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u5zi1acqj"/><path class="f-_5m5bnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:legal-calendar" /></template>
<style>
.f-_5m5bnq {
  d: path("m13.5 18.5l1.25-2.75L16 18.5a1.25 1.25 0 0 1-2.5 0Zm6 0l1.25-2.75L22 18.5a1.25 1.25 0 0 1-2.5 0Z");
}

.u5zi1acqj {
  d: path("M10.9 20H3V4.5h16.5v6.7M3 9.5h11.5m.5 0h4.5m-12-7v4m7.5-4v4m2.75 7.5v7.5m-1.5 0h3m-4.5-5.75h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
