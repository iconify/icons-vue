<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h7ub78bap"/><path class="accbv0bzp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deliverable-at-risk" /></template>
<style>
.accbv0bzp {
  d: path("m2.5 6.75l8 4.25l8-4.25m-8 4.25v9.5m7.5-5.75v3.5M18 21h.01");
}

.h7ub78bap {
  d: path("m15.169 18.02l-3.848 2.044q-.19.101-.398.153t-.423.052t-.423-.052t-.398-.153l-6.25-3.32q-.105-.056-.201-.125t-.182-.151q-.086-.081-.161-.174q-.074-.092-.135-.194t-.108-.211t-.078-.223t-.048-.232t-.016-.236V7.802q0-.119.016-.236q.016-.118.048-.232q.031-.114.078-.223T2.75 6.9t.135-.194t.161-.174t.182-.151t.201-.125l6.25-3.32q.19-.101.398-.153t.423-.052t.423.052t.398.153l6.25 3.32q.105.056.201.125t.182.151t.161.174t.135.194t.108.211t.078.223q.032.114.048.232q.016.117.016.236v4.219");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
