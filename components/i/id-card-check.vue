<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e3zbe68tt"/><path class="om965257j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:id-card-check" /></template>
<style>
.e3zbe68tt {
  d: path("M11.8 19H2.5V5h19v7.3m-19-2.8h19");
}

.om965257j {
  d: path("M5.5 8.5h4V15h-4Zm8 .5h5m-3.75 9l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
