<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nht-2qqgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-emergency-kit" /></template>
<style>
.nht-2qqgw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.8 17H2.5V5h17v7.4M8.5 5V3.5a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1V5M11 8v6m-3-3h6m.5 9v-2.25l1.25-2.5h4.5l1.25 2.5V20Zm1.5 0v1.5m4-1.5v1.5");
}

</style>
