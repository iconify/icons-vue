<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e6cvfq3zf"/><path class="pflefjb-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arrive-home" /></template>
<style>
.e6cvfq3zf {
  d: path("M10 12.5V11l5.5-5l5.5 5v9H10v-1.5m-7.5-3h11");
}

.pflefjb-l {
  d: path("m11.25 13.25l2.25 2.25l-2.25 2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
