<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guloiabxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cell-search" /></template>
<style>
.guloiabxp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.813 4.813Q2.25 7.376 2.25 11t2.563 6.187T11 19.75q1.413 0 2.665-.39q-.415-.844-.415-1.86q0-1.76 1.245-3.005T17.5 13.25q1.016 0 1.86.415q.39-1.252.39-2.665q0-3.624-2.563-6.187T11 2.25T4.813 4.813M7.25 11q0-3.75 3.75-3.75T14.75 11T11 14.75T7.25 11m10.25 3.5q-3 0-3 3t3 3q.97 0 1.626-.313l1.344 1.343q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.343-1.344q.313-.656.313-1.626q0-3-3-3m0 4.5Q16 19 16 17.5t1.5-1.5t1.5 1.5t-1.5 1.5");
}

</style>
