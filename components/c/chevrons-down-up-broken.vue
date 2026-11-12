<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qgh7ic-3c"/><path class="r07sdub0t"/><path class="fxdm1bc-j"/><path class="sttcv9_ok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevrons-down-up-broken" /></template>
<style>
.fxdm1bc-j {
  d: path("M10.5 16.5L12 15L18 21");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qgh7ic-3c {
  d: path("M10.5 7.5L12 9L18 3");
}

.r07sdub0t {
  d: path("M7.5 4.5L6 3");
}

.sttcv9_ok {
  d: path("M7.5 19.5L6 21");
}

</style>
