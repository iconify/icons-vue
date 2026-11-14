<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vivpq-brl"/><path class="z-iiq2fio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:electric-cargo-bike" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vivpq-brl {
  d: path("M2.25 15.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m15.432-2.059q-.21-.223-.461-.399q-.251-.175-.533-.297q-.281-.121-.581-.183q-.301-.062-.607-.062q-.147 0-.294.014t-.291.044q-.145.028-.286.071t-.277.099t-.266.126t-.253.152q-.122.081-.236.175t-.218.198q-.105.104-.198.218t-.175.236t-.152.253t-.126.266t-.099.277t-.071.286t-.044.291q-.014.147-.014.294q0 .123.01.246t.03.245q.021.122.051.241q.03.12.07.237t.089.23t.108.221q.058.109.125.213q.067.103.143.201q.075.097.158.188q.083.092.174.176t.187.16t.2.144t.211.128q.108.059.221.109q.112.051.229.092q.116.04.236.072");
}

.z-iiq2fio {
  d: path("M5.25 15.5H10l-2-6h4.5l-2.5 6m4.5-6l1 6m-1.25-12h5A1.75 1.75 0 0 1 21 5.25v2.5a1.75 1.75 0 0 1-1.75 1.75h-5a1.75 1.75 0 0 1-1.75-1.75v-2.5a1.75 1.75 0 0 1 1.75-1.75m6.25 11l-3 3.5h3.25l-3 3.5");
}

</style>
