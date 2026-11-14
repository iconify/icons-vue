<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yot52tbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-balance-ledger" /></template>
<style>
.yot52tbdw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3.5h10.5M13 7h7.5M8 10.5h12.5m-9 3.5h9M4.25 14h2.5M5.5 12.75v2.5M3.5 18h17m-17 3h17");
}

</style>
