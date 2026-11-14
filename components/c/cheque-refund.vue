<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zrccxbbsb"/><path class="txdf6pbob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cheque-refund" /></template>
<style>
.txdf6pbob {
  d: path("M17.5 15.5L15 18l2.5 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zrccxbbsb {
  d: path("M11.6 18.5H2.5v-13h19v9.7m-19-5.7h19M6 9.5h5m-5 5h3.5M21 18h-6");
}

</style>
