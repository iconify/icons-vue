<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="upi1g3sjn"/><path class="s6y2_hmvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:earnest-money" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s6y2_hmvm {
  d: path("M5 11.5L9 15c.5.5 1.25.5 1.75 0l3.5-3h1.625M20 16.25c-.25-.75-1-1.25-2-1.25c-1.1 0-1.75.6-1.75 1.5c0 1.75 3.75 1 3.75 3c0 .9-.75 1.5-2 1.5c-1 0-1.75-.5-2-1.25m2-6V15m0 6v1");
}

.upi1g3sjn {
  d: path("M3.75 5zA1.25 1.25 0 0 1 5 6.25v5.5A1.25 1.25 0 0 1 3.75 13a1.25 1.25 0 0 1-1.25-1.25v-5.5A1.25 1.25 0 0 1 3.75 5M19 11.153V6.25q0-.061.006-.123q.006-.061.018-.121t.03-.119t.041-.115q.024-.057.053-.111t.063-.105t.073-.099t.082-.091q.044-.043.091-.082t.099-.073q.051-.034.105-.063t.111-.053t.115-.041t.119-.03q.06-.012.121-.018Q20.189 5 20.25 5t.123.006q.061.006.121.018t.119.03t.115.041q.057.024.111.053t.105.063t.099.073t.091.082t.082.091t.073.099t.063.105t.053.111q.023.056.041.115t.03.119t.018.121q.006.062.006.123v5.5q0 .087-.012.173t-.036.169t-.059.163t-.08.153q-.046.074-.101.141t-.12.125q-.064.058-.136.107q-.071.049-.149.088M19 6.5h-3.5L11 10c-.75.6-.5 1.75.5 1.75h1L15 10M5 6.5h3L10.25 8");
}

</style>
