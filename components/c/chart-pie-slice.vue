<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x2gqfgbep"/><path class="bsi_sac1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-pie-slice" /></template>
<style>
.bsi_sac1g {
  d: path("M4.5 10.5a9 9 0 0 1 9 9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x2gqfgbep {
  d: path("M4.5 19.5v-15a15 15 0 0 1 15 15Z");
}

</style>
