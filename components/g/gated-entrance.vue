<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8bq_xbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gated-entrance" /></template>
<style>
.d8bq_xbwc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 3Q1.75 3 1.75 5.75q0 1.314.628 2q-.628.561-.628 1.75V20q0 2.25 2.25 2.25h1q.599 0 1.038-.159q.099.077.218.118q.118.041.244.041h11q.126 0 .244-.041q.119-.041.218-.118q.439.159 1.038.159h1q2.25 0 2.25-2.25V9.5q0-1.189-.628-1.75q.628-.686.628-2Q22.25 3 19.5 3t-2.75 2.75q0 1.314.628 2q-.628.561-.628 1.75v.92q-.916-.352-1.842.162l-.007.004l-.03.017l-1.463.812q-1.158.643-1.158 1.968v3.914q0 1.805 1.763 2.196l1.052.234q.022.006.045.01l.402.089q.661.147 1.238-.064V20q0 .413.076.75H7.174q.076-.337.076-.75v-.238q.577.211 1.238.064l.402-.089q.023-.004.045-.01l1.052-.234q1.763-.391 1.763-2.196v-3.914q0-1.325-1.158-1.968l-1.463-.812l-.03-.017l-.007-.004q-.926-.514-1.842-.162V9.5q0-1.189-.628-1.75q.628-.686.628-2Q7.25 3 4.5 3");
}

</style>
