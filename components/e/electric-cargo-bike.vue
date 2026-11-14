<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ukxfpqbvo"/><path class="q3qyjs8nk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:electric-cargo-bike" /></template>
<style>
.q3qyjs8nk {
  d: path("M5.25 15.5H10l-2-6h4.5l-2.5 6m4.5-6l1 6m-3-12H21v6h-8.5Zm8 11l-3 3.5h3.25l-3 3.5");
}

.ukxfpqbvo {
  d: path("M2.25 15.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm15.432-2.059q-.21-.223-.461-.399q-.251-.175-.533-.297q-.281-.121-.581-.183q-.301-.062-.607-.062q-.147 0-.294.014t-.291.044q-.145.028-.286.071t-.277.099t-.266.126t-.253.152q-.122.081-.236.175t-.218.198q-.105.104-.198.218t-.175.236t-.152.253t-.126.266t-.099.277t-.071.286t-.044.291q-.014.147-.014.294q0 .181.022.362q.022.18.065.356t.108.346q.064.17.149.33q.084.161.187.31q.103.15.224.285q.12.136.256.257q.136.12.285.223");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
