<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w7ibfe3_f"/><path class="ujnm16bwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:input-number" /></template>
<style>
.ujnm16bwc {
  d: path("m15.5 10.25l1.5-1.5l1.5 1.5m-3 3.5l1.5 1.5l1.5-1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w7ibfe3_f {
  d: path("M2.5 6h19v12h-19ZM6 12h5");
}

</style>
