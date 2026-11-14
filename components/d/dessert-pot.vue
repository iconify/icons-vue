<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iktz-pw0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dessert-pot" /></template>
<style>
.iktz-pw0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9h13M5 9l1.5 10h6L14 9M5 9a4.5 3.5 0 0 1 9 0m-1.25-2.5L16 3m-.5 15.5h6M17 16l3 5m0-5l-3 5");
}

</style>
