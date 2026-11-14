<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jm5wi--od"/><path class="qowo29bly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:invoice-batch" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jm5wi--od {
  d: path("M13.5 20.1v.9l-1.75-1.25L10 21l-2-1.25L6 21l-1.75-1.25L2.5 21V6h11v10.4m0 .2v3.3");
}

.qowo29bly {
  d: path("M6 6V3h11.5v7.5m-12-.5h5m-5 4H9m10.75 2.25C19.5 15.5 18.9 15 18 15c-1.05 0-1.75.6-1.75 1.5c0 1.6 3.5.9 3.5 3c0 .9-.75 1.5-1.75 1.5c-.9 0-1.55-.4-1.75-1M18 13.75V15m0 6v1");
}

</style>
