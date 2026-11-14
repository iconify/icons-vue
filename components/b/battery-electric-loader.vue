<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e49wvgb5i"/><path class="z9sjr-ccv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:battery-electric-loader" /></template>
<style>
.e49wvgb5i {
  d: path("M2.5 15v-4H11V4.5h4V15Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z9sjr-ccv {
  d: path("M2.5 11V7.5a1 1 0 0 1 1-1h.75V5h2.5v1.5h.75a1 1 0 0 1 1 1V11M15 7l4.75 4.5m-1.75 0h3.5l-1 6H18ZM3.5 17A2.25 2.25 0 1 0 8 17a2.25 2.25 0 1 0-4.5 0m7 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

</style>
