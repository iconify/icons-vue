<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su9b87nlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:follow-request-accept" /></template>
<style>
.su9b87nlv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 8.25q0-1.864 1.318-3.182T9 3.75t3.182 1.318T13.5 8.25t-1.318 3.182T9 12.75t-3.182-1.318T4.5 8.25m10 2.5q0-4 4-4t4 4t-4 4t-4-4m1.5 0q0 2.5 2.5 2.5t2.5-2.5t-2.5-2.5t-2.5 2.5m2.208-.103l-.428-.427q-.052-.053-.113-.094t-.13-.069t-.141-.043T17.25 10t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243t-.057.287t.057.287t.163.243l1 1q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.021-.02.039-.042l1.5-1.75q.098-.113.144-.255t.035-.291q-.012-.148-.079-.281q-.068-.133-.181-.23q-.056-.049-.12-.085q-.065-.036-.135-.059t-.144-.032q-.073-.008-.147-.003q-.073.006-.144.026t-.137.053t-.124.079t-.106.102zM3.963 15.985Q1.75 17.573 1.75 20q0 1.75 1.75 1.75h11q1.75 0 1.75-1.75q0-2.427-2.213-4.015Q11.97 14.5 9 14.5t-5.037 1.485");
}

</style>
