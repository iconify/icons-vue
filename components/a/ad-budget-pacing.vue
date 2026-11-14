<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w82e6zvtb"/><path class="duporv-yi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ad-budget-pacing" /></template>
<style>
.duporv-yi {
  d: path("M18.75 17c-.25-.5-.5-.5-.75-.5q-.75 0-.75.75c0 .5 1.5.5 1.5 1.5q0 .75-.75.75c-.5 0-.75-.25-.75-.5m.75-3.25v.75m0 3v.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w82e6zvtb {
  d: path("M3 2.5h9.5M3 21.5h9.2m-7.95-19V5c0 3 3.5 5 3.5 7s-3.5 4-3.5 7v2.5m7-19V5c0 3-3.5 5-3.5 7s3.5 4 3.5 7v2.5M14 18a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

</style>
