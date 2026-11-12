<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lcxm2bc4c"/><path class="rasqg796i"/><path class="i87_9e8dl"/><path class="ko6o-6b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:basketball-broken" /></template>
<style>
.i87_9e8dl {
  d: path("M16.4131 3.20896C14.9252 7.63002 7.67345 12.5123 2.28779 11.4516");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ko6o-6b9b {
  d: path("M7 3.33782C8.47087 2.48697 10.1786 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 10.1786 2.48697 8.47087 3.33782 7");
}

.lcxm2bc4c {
  d: path("M16.9503 20.5732C16.9503 20.5732 16.0113 13.9821 14.001 10.5C11.9906 7.01801 7.05078 3.42679 7.05078 3.42679");
}

.rasqg796i {
  d: path("M7.57739 20.8175C9.05903 16.3477 16.4528 11.393 21.8638 12.5801");
}

</style>
