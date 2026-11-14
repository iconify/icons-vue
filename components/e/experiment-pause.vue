<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvo_t4ehq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:experiment-pause" /></template>
<style>
.hvo_t4ehq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.5v6L4.25 19.25q-.024.042-.046.085l-.04.088q-.018.045-.034.091q-.016.045-.029.092l-.022.094q-.01.047-.016.095q-.007.048-.01.096q-.004.049-.004.097q-.001.048.002.097l.008.096q.006.048.015.095q.009.048.021.095t.027.093t.033.091t.038.088q.021.044.044.086q.024.043.05.083t.055.08t.06.076t.064.072q.034.034.07.067q.035.033.073.063t.077.058q.04.028.081.053t.084.048t.087.042t.09.036t.091.031q.047.014.094.025t.095.018t.096.013l.096.006h7.95m2.814-8.768L14 8.5v-6m-5.5 0h7m.75 13v6m4-6v6");
}

</style>
