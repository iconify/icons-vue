<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxsf_lgfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:display-plinth" /></template>
<style>
.nxsf_lgfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 2.5h13A1.5 1.5 0 0 1 20 4a1.5 1.5 0 0 1-1.5 1.5h-13A1.5 1.5 0 0 1 4 4a1.5 1.5 0 0 1 1.5-1.5m2.5 3h8A1.5 1.5 0 0 1 17.5 7v10.5A1.5 1.5 0 0 1 16 19H8a1.5 1.5 0 0 1-1.5-1.5V7A1.5 1.5 0 0 1 8 5.5M6.25 19h11.5A1.25 1.25 0 0 1 19 20.25a1.25 1.25 0 0 1-1.25 1.25H6.25A1.25 1.25 0 0 1 5 20.25A1.25 1.25 0 0 1 6.25 19M14.5 5.5V19");
}

</style>
