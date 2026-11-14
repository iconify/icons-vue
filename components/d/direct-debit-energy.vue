<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvvnmfbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:direct-debit-energy" /></template>
<style>
.lvvnmfbpv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.1 13H3V3h15v9.1M5.5 16q0 .147.014.294t.044.291q.028.145.071.286t.099.277q.057.136.126.266q.07.13.152.253q.081.122.175.236t.198.218t.218.198t.236.175q.123.082.253.152t.266.126t.277.099t.286.071t.291.044T8.5 19h2.608m-.608-2l1.273 1.273M3 6.5h15m1.5 8l-3.75 3.75h4.5L16.5 22");
}

</style>
