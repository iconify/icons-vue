<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukq-_abbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:checkout-receipt-total" /></template>
<style>
.ukq-_abbv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h14v18l-3.5-2l-3.5 2l-3.5-2L5 21Zm3.5 4h3m-3 3.5h3m4-3.5h.01m-.01 3.5h.01m-7.01 4h7");
}

</style>
