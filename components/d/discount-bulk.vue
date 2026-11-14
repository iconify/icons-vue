<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ziaic_wyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:discount-bulk" /></template>
<style>
.ziaic_wyd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5H11A1.5 1.5 0 0 1 12.5 4v3A1.5 1.5 0 0 1 11 8.5H6.5A1.5 1.5 0 0 1 5 7V4a1.5 1.5 0 0 1 1.5-1.5M5 8.5h7a1.5 1.5 0 0 1 1.5 1.5v3.5A1.5 1.5 0 0 1 12 15H5a1.5 1.5 0 0 1-1.5-1.5V10A1.5 1.5 0 0 1 5 8.5m8.448 11.893q-.032.118-.083.23q-.051.111-.12.213q-.068.102-.152.191t-.182.164q-.097.075-.205.133q-.109.057-.225.097q-.116.039-.237.059T12 21.5H4q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T2.5 20v-3.5q0-.074.007-.147t.022-.146q.014-.072.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119t.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036t.146-.022T4 15h8q.12 0 .238.019t.232.057t.22.092t.203.127q.096.071.18.156t.152.184q.069.098.122.205q.053.108.088.222M8.75 2.5v2m-.25 4v2M8 15v2m10-2.5V21m-2.75-2.75L18 21l2.75-2.75");
}

</style>
