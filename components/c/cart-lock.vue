<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft8g4tbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cart-lock" /></template>
<style>
.ft8g4tbqt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h2l2.75 9.75h7.37m2.581-1.503L19 5.25H5.25m0 12.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m6.748-.065q-.003-.059-.011-.118t-.023-.116t-.034-.114t-.045-.11t-.054-.105q-.03-.052-.065-.1q-.034-.048-.073-.093t-.082-.086t-.09-.077t-.097-.069t-.103-.059t-.108-.049t-.112-.039t-.115-.028t-.118-.016q-.059-.006-.118-.006q-.061 0-.123.006q-.061.006-.121.018t-.119.03t-.115.041t-.111.053t-.105.063q-.052.034-.099.073t-.091.082q-.043.044-.082.091t-.073.099q-.034.051-.063.105t-.053.111t-.041.115t-.03.119t-.018.121q-.006.062-.006.123t.006.123q.006.061.018.121t.03.119t.041.115q.024.057.053.111t.063.105t.073.099t.082.091q.044.043.091.082t.099.073t.105.063t.111.053q.056.023.115.041t.119.03t.121.018t.123.006q.16 0 .314-.04q.155-.04.295-.118t.255-.188q.115-.111.199-.247m4.437-.907h3.5A1.75 1.75 0 0 1 21.5 19v1a1.75 1.75 0 0 1-1.75 1.75h-3.5A1.75 1.75 0 0 1 14.5 20v-1a1.75 1.75 0 0 1 1.75-1.75m0 0v-1.5a1.75 1.75 0 0 1 3.5 0v1.5");
}

</style>
