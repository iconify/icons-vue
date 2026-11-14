<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucsuwhrus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:growth-chart-bio" /></template>
<style>
.ucsuwhrus {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 15zA1.75 1.75 0 0 1 6 16.75v3a1.75 1.75 0 0 1-1.75 1.75a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 4.25 15m6.25-5.5za1.75 1.75 0 0 1 1.75 1.75v8.5a1.75 1.75 0 0 1-1.75 1.75a1.75 1.75 0 0 1-1.75-1.75v-8.5A1.75 1.75 0 0 1 10.5 9.5m4.5 2.975V4.75q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147q.048-.072.102-.138q.055-.067.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041t.169-.026Q16.664 3 16.75 3t.172.008t.169.026q.085.016.167.041t.162.058t.155.074t.147.088t.138.102t.127.116q.061.06.116.127q.054.066.102.138q.048.071.088.147q.041.076.074.155q.033.08.058.162t.041.167q.017.084.026.169t.008.172v7.925m-2.53 8.641q-.168-.083-.315-.201q-.146-.117-.264-.263q-.118-.145-.203-.313q-.085-.167-.132-.349M18.75 22v-4.25m0 .5c-2.5 0-3.25-1.25-3.25-3c2.25 0 3.25 1 3.25 3m0-.5c0-2 1-3 3.25-3c0 2.25-1.25 3-3.25 3");
}

</style>
