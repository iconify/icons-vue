<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w0uxrybij"/><path class="kevlllbeq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bathroom-count" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kevlllbeq {
  d: path("M15.5 16.75a2.5 2.5 0 0 1 5 0c0 1.5-1.5 2.5-5 4.75h5.25");
}

.w0uxrybij {
  d: path("M12.754 16H7.5q-.123 0-.245-.006q-.123-.006-.245-.018t-.244-.03t-.241-.042q-.121-.024-.24-.054t-.236-.065q-.118-.036-.233-.077q-.116-.042-.229-.089q-.114-.047-.225-.099t-.219-.11t-.214-.121t-.207-.132t-.2-.141t-.194-.151t-.186-.16q-.091-.083-.178-.169q-.086-.087-.169-.178q-.082-.091-.16-.186t-.151-.194t-.141-.2q-.069-.102-.132-.207q-.063-.106-.121-.214t-.11-.219t-.099-.225q-.047-.113-.089-.229q-.041-.115-.077-.233q-.035-.117-.065-.236t-.054-.24q-.024-.12-.042-.241q-.018-.122-.03-.244t-.018-.245T2.5 11V9.5h19V11q0 .787-.242 1.537M5 9.5v-5a2.25 2.25 0 0 1 4.5 0M6.5 16v2.5");
}

</style>
