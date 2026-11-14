<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="riazqubxv"/><path class="z5dhh8blc"/><path class="v-kojjb-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cart-sync" /></template>
<style>
.riazqubxv {
  d: path("M2.5 3h2l2.75 9.75h7.57m2.151-.737L19 5.25H5.25m0 12.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm6.653-.484q-.036-.084-.083-.163q-.048-.078-.106-.149q-.059-.071-.127-.133q-.068-.061-.145-.112t-.159-.09q-.084-.039-.172-.066q-.087-.026-.178-.04q-.091-.013-.183-.013q-.061 0-.123.006q-.061.006-.121.018t-.119.03t-.115.041t-.111.053t-.105.063q-.052.034-.099.073t-.091.082q-.043.044-.082.091t-.073.099q-.034.051-.063.105t-.053.111t-.041.115t-.03.119t-.018.121q-.006.062-.006.123t.006.123q.006.061.018.121t.03.119t.041.115q.024.057.053.111t.063.105t.073.099t.082.091q.044.043.091.082t.099.073t.105.063t.111.053q.056.023.115.041t.119.03t.121.018t.123.006q.233 0 .45-.084q.218-.084.39-.24M15 16.75a3.25 3.25 0 0 1 6 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v-kojjb-r {
  d: path("m14.25 21l.75-1.75l1.75.75");
}

.z5dhh8blc {
  d: path("M21.75 15L21 16.75L19.25 16M21 19.25a3.25 3.25 0 0 1-6 0");
}

</style>
