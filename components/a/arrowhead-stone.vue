<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-l98sqlu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arrowhead-stone" /></template>
<style>
.d-l98sqlu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m19.341 6.59l-1.172 3.127a.765.765 0 0 1-1.419.033l-.514-1.199a1.5 1.5 0 0 0-.787-.787L14.25 7.25a.765.765 0 0 1 .033-1.419l3.127-1.172a1.5 1.5 0 0 1 1.931 1.931M16 8L3.5 20.5");
}

</style>
