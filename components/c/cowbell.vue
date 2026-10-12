<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcltgt-je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cowbell" /></template>
<style>
.lcltgt-je {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 7h5q1 0 1.26.97l2.98 11.06Q17 20 16 20H4q-1 0-.74-.97L6.24 7.97Q6.5 7 7.5 7m1 0V5.25a1.5 1.5 0 0 1 3 0V7M3.81 17h12.38m5.06-14L17 7.25");
}

</style>
