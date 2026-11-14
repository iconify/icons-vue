<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="crfrnebpk"/><path class="zcqhsvbel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coverage-indoor" /></template>
<style>
.crfrnebpk {
  d: path("M3 20.5V10l9-7l9 7v10.5Zm9-3.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zcqhsvbel {
  d: path("M9.525 14.525a3.5 3.5 0 0 1 4.95 0m-7.071-2.121a6.5 6.5 0 0 1 9.192 0");
}

</style>
