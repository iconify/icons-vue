<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prcgj--5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kebab-shop" /></template>
<style>
.prcgj--5i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.498 6h9.004a1.75 1.75 0 0 1 1.644 2.348l-2.727 7.5A1.75 1.75 0 0 1 13.774 17h-3.548a1.75 1.75 0 0 1-1.645-1.152l-2.727-7.5A1.75 1.75 0 0 1 7.498 6M12 2.5V6m0 11v4.5m-6-2h12M6 8.75h3.5m3.5 5.5h3");
}

</style>
