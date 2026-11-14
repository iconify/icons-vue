<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g28zfm4dz"/><path class="qyyk4hkuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-windshield-crack" /></template>
<style>
.g28zfm4dz {
  d: path("m4.815 14.738l1.688-6.75A2.625 2.625 0 0 1 9.05 6h5.9a2.625 2.625 0 0 1 2.547 1.988l1.688 6.75A2.625 2.625 0 0 1 16.638 18H7.362a2.625 2.625 0 0 1-2.547-3.262");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qyyk4hkuw {
  d: path("m12 6l-1 4l2.5 2.5L12 18m-1-8l-3 1.5");
}

</style>
