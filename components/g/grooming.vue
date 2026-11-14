<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q156s3bqa"/><path class="fdxqc5m1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grooming" /></template>
<style>
.fdxqc5m1s {
  d: path("m13.743 8.136l2.121 2.121L5.257 20.864l-2.121-2.121ZM11 5V3.25l1-.75M14 5V3.25l1-.75M17 5V3.25l1-.75M20 5V3.25l1-.75");
}

.q156s3bqa {
  d: path("M9 5h12v3.5H9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
