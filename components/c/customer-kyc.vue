<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e3zbe68tt"/><path class="t7dnemvks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:customer-kyc" /></template>
<style>
.e3zbe68tt {
  d: path("M11.8 19H2.5V5h19v7.3m-19-2.8h19");
}

.t7dnemvks {
  d: path("M5.5 10A1.75 1.75 0 1 0 9 10a1.75 1.75 0 1 0-3.5 0Zm-.75 5.75C5 14.4 6 13.5 7.25 13.5s2.25.9 2.5 2.25M13 9.25h5M14.75 18l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
