<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ly1hmfbvj"/><path class="qm98t-bpr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:large-print-sign" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ly1hmfbvj {
  d: path("M6.5 2.5h11A3.5 3.5 0 0 1 21 6v7.5a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 13.5V6a3.5 3.5 0 0 1 3.5-3.5M12 17v4.5");
}

.qm98t-bpr {
  d: path("m8 14l4-8.5l4 8.5m-6.75-2.5h5.5");
}

</style>
