<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ytsosdwtx"/><path class="k5vmw3b4g"/><path class="cf6mjrbtj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:income-tax-refund" /></template>
<style>
.cf6mjrbtj {
  d: path("m9.5 17.5l-2.25 2.25L9.5 22");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k5vmw3b4g {
  d: path("M9.5 8.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M17 14v3.5a2.25 2.25 0 0 1-2.25 2.25h-7.5");
}

.ytsosdwtx {
  d: path("M6 3.5h12A3.5 3.5 0 0 1 21.5 7v3.5A3.5 3.5 0 0 1 18 14H6a3.5 3.5 0 0 1-3.5-3.5V7A3.5 3.5 0 0 1 6 3.5");
}

</style>
