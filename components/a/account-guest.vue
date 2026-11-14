<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qla-_4-yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-guest" /></template>
<style>
.qla-_4-yi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.327 9.435a4 4 0 0 1 0-4.87m2.651-1.531a4 4 0 0 1 4.218 2.435m0 3.062a4 4 0 0 1-4.218 2.435M3 19.5c0-1.5.75-2.75 2-3.75m3.25-1.25c.75-.25 1.5-.5 2.25-.5s1.5.25 2.25.5M16 15.75c1.25 1 2 2.25 2 3.75m-11.75 1h8.5");
}

</style>
