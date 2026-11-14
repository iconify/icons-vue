<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3hvu78zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:keyword-gap" /></template>
<style>
.u3hvu78zw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.625 7.5h.75A2.625 2.625 0 0 1 15 10.125v3.75a2.625 2.625 0 0 1-2.625 2.625h-.75A2.625 2.625 0 0 1 9 13.875v-3.75A2.625 2.625 0 0 1 11.625 7.5M2.5 4.5h19M2.5 12h3.75m11.5 0h3.75m-19 7.5h12");
}

</style>
