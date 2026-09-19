<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="fc4h_3bnk"/><circle class="qp-5w9khw"/><path class="fag822b-i"/><circle class="e7ku7bcgt"/><circle class="ja-2b-zsl"/><circle class="qlwkes_zx"/><path class="hnswz4e7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gamenative" /></template>
<style>
.e7ku7bcgt {
  cx: 32.155px;
  cy: 15.846px;
  r: 3.121px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fag822b-i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.775 35.275C9.558 35.275 4.5 30.217 4.5 24s5.058-11.275 11.275-11.275a3.12 3.12 0 1 1 0 6.242c-2.776 0-5.033 2.257-5.033 5.033s2.257 5.034 5.033 5.034S20.81 26.776 20.81 24a3.12 3.12 0 1 1 6.241 0c0 6.217-5.059 11.275-11.276 11.275");
}

.fc4h_3bnk {
  cx: 15.775px;
  cy: 24px;
  r: 1.89px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hnswz4e7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.276 15.689v8.977m-6.242 7.331v-8.536m13.542 2.755l-8.225 8.154m-4.393-4.432l8.225-8.154m-16.418-.031l8.166-8.098m4.447 4.381l-7.439 7.55m-9.65-2.834h3.783m-.421 2.496H17.29");
}

.ja-2b-zsl {
  cx: 32.155px;
  cy: 32.154px;
  r: 3.121px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qlwkes_zx {
  cx: 40.379px;
  cy: 24px;
  r: 3.121px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qp-5w9khw {
  cx: 23.896px;
  cy: 24px;
  r: 1.248px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
