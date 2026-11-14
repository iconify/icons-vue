<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1xuxozus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:body-weight" /></template>
<style>
.d1xuxozus {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 2.25h7.5q2.485 0 4.243 1.757Q21.75 5.765 21.75 8.25v7.5q0 2.485-1.757 4.243q-1.758 1.757-4.243 1.757h-7.5q-2.485 0-4.243-1.757Q2.25 18.235 2.25 15.75v-7.5q0-2.485 1.757-4.243Q5.765 2.25 8.25 2.25m4.681 7.012l-1.5 1.75q-.049.056-.085.12q-.036.065-.059.135t-.032.144q-.008.073-.003.147q.006.073.026.144t.053.137t.079.124t.102.106t.12.085q.065.036.135.059t.144.032q.073.008.147.003q.073-.006.144-.026t.137-.053t.124-.079t.106-.102l1.5-1.75q.049-.056.085-.12q.036-.065.059-.135t.032-.144q.008-.073.003-.147q-.006-.073-.026-.144t-.053-.137t-.079-.124t-.102-.106t-.12-.085q-.065-.036-.135-.059t-.144-.032q-.073-.008-.147-.003q-.073.006-.144.026t-.137.053t-.124.079t-.106.102");
}

</style>
