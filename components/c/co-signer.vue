<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe-eibkut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:co-signer" /></template>
<style>
.xe-eibkut {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11h19m-19 9.5h19M3.5 8C5 4 7 3 7 5s-1 3.5.5 3.5s2.5-3 4-3S12.5 8 14 8s2.5-1.5 4-1.5m-14.5 11C5 15.5 6 14 7 14s.5 3.5 2 3.5s2.5-3 4-3s1 2.5 2.5 2.5");
}

</style>
