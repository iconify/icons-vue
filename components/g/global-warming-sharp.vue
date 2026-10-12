<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="rmn0_9bsr"/><path class="crznlouwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:global-warming-sharp" /></template>
<style>
.crznlouwo {
  d: path("M3.25 13.5h14.5M10.5 6.25a3.25 7.25 0 0 1 0 14.5a3.25 7.25 0 0 1 0-14.5m8 3.75V2.75M16 5.25l2.5-2.5l2.5 2.5");
}

.rmn0_9bsr {
  cx: 10.5px;
  cy: 13.5px;
  r: 7.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
