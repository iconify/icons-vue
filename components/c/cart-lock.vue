<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umfdmwtry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cart-lock" /></template>
<style>
.umfdmwtry {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h2l2.75 9.75h7.37m2.581-1.503L19 5.25H5.25m0 12.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm6.477-.78q-.088-.11-.198-.198q-.11-.087-.237-.148t-.264-.093q-.137-.031-.278-.031q-.061 0-.123.006q-.061.006-.121.018t-.119.03t-.115.041t-.111.053t-.105.063q-.052.034-.099.073t-.091.082q-.043.044-.082.091t-.073.099q-.034.051-.063.105t-.053.111t-.041.115t-.03.119t-.018.121q-.006.062-.006.123t.006.123q.006.061.018.121t.03.119t.041.115q.024.057.053.111t.063.105t.073.099t.082.091q.044.043.091.082t.099.073t.105.063t.111.053q.056.023.115.041t.119.03t.121.018t.123.006q.145 0 .286-.033t.271-.098t.242-.157t.199-.209M14.5 17.25h7v4.5h-7Zm1.75 0v-1.5a1.75 1.75 0 0 1 3.5 0v1.5");
}

</style>
