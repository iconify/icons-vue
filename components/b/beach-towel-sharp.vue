<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ycdjlfbmq"/><path class="pkfaybc1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:beach-towel-sharp" /></template>
<style>
.pkfaybc1g {
  d: path("M8.5 11.5h12.75l-.7 1.32l-2.85 5.36l-.7 1.32H2.75l.7-1.32l2.85-5.36l.7-1.32zm3.25 0l-4.25 8m9-8l-4.25 8");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ycdjlfbmq {
  cx: 6.5px;
  cy: 5.75px;
  r: 2.25px;
}

</style>
