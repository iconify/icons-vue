<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fdpdqbbys"/><path class="z7_varc1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kpi-down" /></template>
<style>
.fdpdqbbys {
  d: path("M2.5 4.5h19v15h-19ZM6 9h4m-4 5.5h4m5.5-6v7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z7_varc1p {
  d: path("m13 13l2.5 2.5L18 13");
}

</style>
