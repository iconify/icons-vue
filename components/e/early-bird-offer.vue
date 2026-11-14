<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rpeo41mbi"/><path class="akeikbc4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:early-bird-offer" /></template>
<style>
.akeikbc4j {
  d: path("m19.431 6.429l.199.073a.694.694 0 0 1 .12 1.248l-.173.104a.796.796 0 0 1-1.202-.604a.79.79 0 0 1 1.056-.821M15.25 6.25h.01M7.5 12c1.5 2 4 2.5 6 1M9 18v2.5m-5.5-8l-1-3m12.25 11.75l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rpeo41mbi {
  d: path("M13.225 17.212A6.8 6.8 0 0 1 10 18c-3.75 0-6.5-2.25-6.5-5.5c0-3.5 3-5.75 7-5.5c.5-2.25 2.25-3.5 4.5-3.5s3.75 1.75 3.5 4c-.25 2-1.25 3.25-2 4q-.001.702-.119 1.34");
}

</style>
