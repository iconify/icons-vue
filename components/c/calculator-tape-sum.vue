<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyuradb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calculator-tape-sum" /></template>
<style>
.qyuradb7c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 10h15v11.5h-15Zm3 0V2.5h9V10m-6.25-4h3.5m-5.5 8h.01M12 14h.01m3.74 0h.01m-7.51 4h.01M12 18h.01m3.74 0h.01");
}

</style>
