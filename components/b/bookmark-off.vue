<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgjt_qbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bookmark-off" /></template>
<style>
.wgjt_qbff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.28 3.371q.305-.182.648-.277Q8.27 3 8.625 3h6.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087t.232.11q.114.061.221.132q.108.072.207.154q.1.082.191.173t.173.191t.154.207t.132.221t.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v8.432m-3.611 4.235l-.814-.611q-.085-.063-.174-.12t-.183-.105q-.093-.049-.19-.091q-.098-.041-.198-.074q-.1-.034-.203-.059q-.102-.025-.207-.042q-.104-.017-.209-.026T12 17.156t-.211.008q-.105.009-.209.026q-.105.017-.207.042q-.103.025-.203.059t-.198.074q-.097.042-.19.091q-.094.049-.183.105q-.089.057-.174.12L9 18.75q-.104.078-.218.141q-.113.063-.235.109q-.121.047-.248.076q-.126.03-.256.041q-.129.012-.259.006t-.257-.031q-.128-.024-.251-.065q-.123-.042-.24-.1t-.223-.132q-.107-.073-.203-.161t-.179-.188t-.151-.21t-.121-.23q-.052-.119-.088-.244t-.053-.253Q6 17.38 6 17.25V9.912M3.5 3.5l17 17");
}

</style>
