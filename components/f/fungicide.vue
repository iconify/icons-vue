<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8rekn9wo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fungicide" /></template>
<style>
.f8rekn9wo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11.5c0-6 4-9 8.5-9s8.5 3 8.5 9Zm5.5 0v7q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022T9.5 20h1q.074 0 .147-.007t.146-.022t.142-.036q.071-.021.139-.049t.133-.063t.126-.076q.062-.041.119-.087q.057-.047.109-.099t.099-.109q.046-.057.087-.119t.076-.126q.035-.065.063-.133t.049-.139q.022-.07.036-.142q.015-.073.022-.146T12 18.5v-.357m0-.3V11.5m2.75 6.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm1 2.25l4.5-4.5");
}

</style>
