<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x0n0kebpl"/><path class="a5wc7ebvv"/><path class="ucatdgbji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deposit-bank-bonds" /></template>
<style>
.a5wc7ebvv {
  d: path("M8.25 18.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

.ucatdgbji {
  d: path("M11 15.75h1.5a2.75 2.75 0 0 1 0 5.5H11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x0n0kebpl {
  d: path("M5.584 19.898q-.295-.063-.584-.148q-.214-.667-.322-1.358T4.57 17q0-.7.108-1.392q.108-.691.322-1.358q-.214-.667-.322-1.358T4.57 11.5t.108-1.392T5 8.75q-.214-.667-.322-1.358T4.57 6t.108-1.392T5 3.25q.548-.161 1.113-.242q.566-.081 1.137-.081t1.137.081T9.5 3.25q.548-.161 1.113-.242q.566-.081 1.137-.081t1.137.081q.565.081 1.113.242q.548-.161 1.113-.242q.566-.081 1.137-.081t1.137.081q.565.081 1.113.242q.214.667.322 1.358T18.93 6t-.108 1.392T18.5 8.75q.214.667.322 1.358t.108 1.392t-.108 1.392t-.322 1.358q.214.667.322 1.358T18.93 17q0 .7-.108 1.392q-.108.691-.322 1.358q-.289.085-.584.148M8.5 8H15m-6.5 3.5H15");
}

</style>
