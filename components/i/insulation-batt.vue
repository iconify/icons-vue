<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tmrp1qt7t"/><path class="fe4w1acdh"/><path class="cfm5kzbhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:insulation-batt" /></template>
<style>
.cfm5kzbhw {
  d: path("M5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm9.75 0c1.25-1.25 2.75 1.25 4 0");
}

.fe4w1acdh {
  d: path("M7 7c2.5-1 4.5 1 7.25 0S19 8 21.5 7v10H7");
}

.tmrp1qt7t {
  d: path("M2 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
