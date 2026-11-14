<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l2brfeq1j"/><path class="d4zu1cv9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bbq-restaurant" /></template>
<style>
.d4zu1cv9q {
  d: path("M7 20.5V15h4v5.5m3.5-4h7a3.5 3.5 0 0 1-7 0Zm1.5 2.75l-1 2.5m5-2.5l1 2.5m-4.25-7.25c-.75-1 .75-2 0-3m2.5 3c-.75-1 .75-2 0-3");
}

.l2brfeq1j {
  d: path("M3 3h18v4H3Zm1.5 4v13.5h8m7-12.7V7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
