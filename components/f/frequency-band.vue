<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpr_gdcdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:frequency-band" /></template>
<style>
.cpr_gdcdm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12C4 7.5 5.75 7.5 7.25 12s3.25 4.5 4.75 0s3.25-4.5 4.75 0s3.25 4.5 4.75 0m-19-6.5h19m-19 13h19");
}

</style>
