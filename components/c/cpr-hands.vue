<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqp1f9bbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cpr-hands" /></template>
<style>
.fqp1f9bbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4.75a1.25 1.25 0 0 1 2.5 0a1.25 1.25 0 0 1 2.5 0a1.25 1.25 0 0 1 2.5 0a1.25 1.25 0 0 1 2.5 0V7a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2Zm2.5 0v2m2.5-2v2m2.5-2v2M4 3.5v5M2.75 7.25L4 8.5l1.25-1.25M20 3.5v5m-1.25-1.25L20 8.5l1.25-1.25m-9.25 14c-.4 0-6-3.25-6-6.75a3 3 0 0 1 5.25-2a.75.75 0 0 0 1.5 0a3 3 0 0 1 5.25 2c0 3.5-5.6 6.75-6 6.75");
}

</style>
