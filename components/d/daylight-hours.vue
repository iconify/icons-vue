<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nxy2ux8uh"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:daylight-hours" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nxy2ux8uh {
  d: path("M7 13q0-.123.006-.245q.006-.123.018-.245t.03-.244t.042-.241q.024-.121.054-.24t.065-.236t.077-.233t.089-.229q.047-.114.099-.225t.11-.219t.121-.214t.132-.207t.141-.2t.151-.194t.16-.186q.083-.091.169-.178q.087-.086.178-.169q.091-.082.186-.16t.194-.151t.2-.141q.102-.069.207-.132q.106-.063.214-.121t.219-.11t.225-.099q.113-.047.229-.089q.115-.041.233-.077q.117-.035.236-.065t.24-.054q.12-.024.241-.042q.122-.018.244-.03t.245-.018T12 8q.215 0 .43.019q.215.018.427.055t.42.092t.411.128t.399.162t.383.197q.187.106.365.228q.177.122.343.259t.321.288t.294.314t.266.338t.236.36t.204.379t.171.395t.137.409t.1.418M2.5 13h12.1M12 2.5v2.75M6.5 7.5L4.75 5.75M17.5 7.5l1.75-1.75M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>
