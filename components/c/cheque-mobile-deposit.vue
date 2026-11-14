<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dtq-hy7hv"/><path class="wmo64rr1v"/><path class="rfpnalb7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cheque-mobile-deposit" /></template>
<style>
.dtq-hy7hv {
  d: path("M2 5h20v14H2Z");
}

.rfpnalb7x {
  d: path("M11.5 13.5c.75-.75 1.25.5 2-.25c.5-.5 1 .5 2 .25M4.25 12h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wmo64rr1v {
  d: path("M6.5 7.75H18v8.5H6.5ZM9 10.5h3.5");
}

</style>
