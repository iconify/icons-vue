<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="biz1ygbiv"/><path class="zo_tvuf4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dashboard-edit" /></template>
<style>
.biz1ygbiv {
  d: path("M11.8 21.5H2.5v-19h19v10.1m0 7.8v1.1h-1.1M2.5 11h16.6m.8 0h1.6M11 11v10.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zo_tvuf4z {
  d: path("m6 8l3-2.25l3.5 1.5L18 5.5m3.5 11l-4.25 4.25l-2.5.5l.5-2.5l4.25-4.25l2 2m-6.25 2.25l2 2");
}

</style>
