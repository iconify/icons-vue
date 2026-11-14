<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z57jx7vju"/><path class="w-u7zkv4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:invoice-unpaid" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w-u7zkv4i {
  d: path("M6.5 5.5H13v3H6.5Zm0 6.5H13m-6.5 4h3m8.5-1.5V18m0 3h.01");
}

.z57jx7vju {
  d: path("M15.2 19.5H3v-17h13.5v9.2");
}

</style>
