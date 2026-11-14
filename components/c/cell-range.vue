<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ync5iqc-m"/><path class="zqlbdabyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cell-range" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ync5iqc-m {
  d: path("M3 3h18v18H3Zm12 0v18M3 15h18M9 15v6m6-12h6");
}

.zqlbdabyb {
  d: path("M3.75 3.75h10.5v10.5H3.75Z");
}

</style>
