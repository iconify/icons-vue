<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot9mav-ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:burn-in-test" /></template>
<style>
.ot9mav-ue {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.7 17H5V5h12v6.6M9 2.5V5m4-2.5V5M2.5 9H5m-2.5 4H5m12-4h2.5M9 17v2.5m9.25 2a3 3 0 0 1-3-3c0-2 1.75-3 2.75-4c.25 1.5 1.5 1.75 1.75 1q1.5 1.5 1.5 3a3 3 0 0 1-3 3Z");
}

</style>
