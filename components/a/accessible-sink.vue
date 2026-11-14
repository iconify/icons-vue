<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2ho4nbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:accessible-sink" /></template>
<style>
.f2ho4nbss {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.407 14.417q-.45.083-.907.083h-4q-.123 0-.245-.006q-.123-.006-.245-.018t-.244-.03t-.241-.042q-.121-.024-.24-.054t-.236-.065q-.118-.036-.233-.077q-.116-.042-.229-.089q-.114-.047-.225-.099t-.219-.11t-.214-.121t-.207-.132t-.2-.141t-.194-.151t-.186-.16q-.091-.083-.178-.169q-.086-.087-.169-.178q-.082-.091-.16-.186t-.151-.194t-.141-.2q-.069-.102-.132-.207q-.063-.106-.121-.214t-.11-.219t-.099-.225q-.047-.113-.089-.229q-.041-.115-.077-.233q-.035-.117-.065-.236t-.054-.24q-.024-.12-.042-.241q-.018-.122-.03-.244t-.018-.245T2.5 9.5v-1h14v1q0 1-.385 1.924m-1.894 2.271q-.575.373-1.23.577M9 8.5V4.25A1.25 1.25 0 0 1 10.25 3H13v2.25m4 9h.01M17 16v3h2.5l1.5 2.5m-7-3.75a2.75 2.75 0 0 0 3.25 3.75");
}

</style>
