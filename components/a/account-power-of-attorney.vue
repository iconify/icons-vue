<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ekf2s55jf"/><path class="bv_7c1boj"/><path class="q21ccjv6j"/><path class="fcfk0_fuo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-power-of-attorney" /></template>
<style>
.bv_7c1boj {
  d: path("M2.5 21.5H13l7.25-4.75c1-.75.25-2.25-1-1.75l-3.75 2.5m-12-9.25a2 3.25 0 1 0 4 0a2 3.25 0 1 0-4 0");
}

.ekf2s55jf {
  d: path("M2.5 15H6l4 2.5h4.25a1.25 1.25 0 0 1 0 2.5H9.5");
}

.fcfk0_fuo {
  d: path("M5.5 7.5a.75.75 0 1 1-.75.75M13 5v6.5M13 5c-.75-1.75-2.25-2-2.25-1c0 .75 1.25 1 2.25 1m0 0c.75-1.75 2.25-2 2.25-1c0 .75-1.25 1-2.25 1m0 6.5l-1.25 2m1.25-2l1.25 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q21ccjv6j {
  d: path("M5.5 5h13.75a1.75 3.25 0 0 1 0 6.5H5.5");
}

</style>
