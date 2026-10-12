<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wutfak-1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:aperture-ring" /></template>
<style>
.wutfak-1p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 3l7.79 4.5v9L12 21l-7.79-4.5v-9Zm1.18 5.7l-3.44.63l-1.18 3.3l2.26 2.67l3.44-.63l1.18-3.3Zm1.08 5.97L12 21m-1.18-5.7l-6.61 1.2m4.35-3.87L4.21 7.5m5.53 1.83L12 3m1.18 5.7l6.61-1.2m-4.35 3.87l4.35 5.13");
}

</style>
