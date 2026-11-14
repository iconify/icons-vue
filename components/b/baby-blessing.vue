<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpywgv1_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-blessing" /></template>
<style>
.tpywgv1_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.699 14.354q-.591.146-1.199.146h-5q-.123 0-.245-.006q-.123-.006-.245-.018t-.244-.03t-.241-.042q-.121-.024-.24-.054t-.236-.065q-.118-.036-.233-.077q-.116-.042-.229-.089q-.114-.047-.225-.099t-.219-.11t-.214-.121t-.207-.132t-.2-.141t-.194-.151t-.186-.16q-.091-.083-.178-.169q-.086-.087-.169-.178q-.082-.091-.16-.186t-.151-.194t-.141-.2q-.069-.102-.132-.207q-.063-.106-.121-.214t-.11-.219t-.099-.225q-.047-.113-.089-.229q-.041-.115-.077-.233q-.035-.117-.065-.236t-.054-.24q-.024-.12-.042-.241q-.018-.122-.03-.244t-.018-.245T2.5 9.5V8h15v1.5q0 .489-.095.968q-.094.48-.28.932t-.456.86q-.269.407-.613.755M2.5 8a5 5 0 0 1 10 0m-5 6.5L6.75 19m5.75-4.5l-.5 3.25m-9.5-.5q4.933 3.289 9.866.397M18.5 21.75L15.75 19a1.94 1.94 0 0 1 2.75-2.75A1.94 1.94 0 0 1 21.25 19Z");
}

</style>
