<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ty3jakbeu"/><path class="t1uj5ssln"/><path class="dfdk8qbbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:contractor" /></template>
<style>
.dfdk8qbbq {
  d: path("M17.25 16.75v-1.5h2.5v1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t1uj5ssln {
  d: path("M17.186 12.5H3.75q-.061 0-.123-.006q-.061-.006-.121-.018t-.119-.03t-.115-.041t-.111-.053t-.105-.063t-.099-.073t-.091-.082q-.043-.044-.082-.091t-.073-.099t-.063-.105t-.053-.111q-.023-.056-.041-.115t-.03-.119t-.018-.121t-.006-.123t.006-.123t.018-.121t.03-.119t.041-.115q.024-.057.053-.111t.063-.105t.073-.099t.082-.091t.091-.082t.099-.073t.105-.063t.111-.053q.056-.023.115-.041t.119-.03t.121-.018T3.75 10h16.5q.061 0 .123.006q.061.006.121.018t.119.03t.115.041q.057.024.111.053t.105.063t.099.073t.091.082q.043.044.082.091t.073.099t.063.105t.053.111q.023.056.041.115t.03.119t.018.121t.006.123t-.006.123t-.018.121t-.03.119t-.041.115q-.024.057-.053.111t-.063.105t-.073.099t-.082.091q-.044.043-.091.082t-.099.073q-.051.034-.105.063t-.111.053t-.115.041t-.119.03t-.121.018q-.062.006-.123.006h-.464M10 10V2.75M14 10V2.75M17.25 16h2.5a1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 19.75 22h-2.5a1.75 1.75 0 0 1-1.75-1.75v-2.5A1.75 1.75 0 0 1 17.25 16");
}

.ty3jakbeu {
  d: path("M4.5 10a7.5 7.5 0 0 1 15 0");
}

</style>
