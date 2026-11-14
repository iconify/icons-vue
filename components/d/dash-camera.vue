<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jga-dedxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dash-camera" /></template>
<style>
.jga-dedxg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.726 4.285Q12 1.213 2.274 4.285q-.07.022-.135.058q-.065.035-.121.083q-.057.047-.103.105t-.08.123t-.055.136t-.027.145t.001.147q.009.073.031.144q.045.142.141.256t.228.183t.281.082t.291-.032Q6.988 4.369 11.25 4.26v2.49H7.375q-2.123 0-3.624 1.501T2.25 11.875v2.75q0 2.123 1.501 3.624t3.624 1.501h9.25q2.123 0 3.624-1.501t1.501-3.624v-2.75q0-2.123-1.501-3.624T16.625 6.75H12.75V4.26q4.262.109 8.524 1.455q.071.022.144.031q.073.008.147.001q.074-.006.145-.027t.136-.055t.123-.08t.105-.103t.083-.121t.058-.135q.045-.142.032-.291t-.082-.281t-.183-.228t-.256-.141M10.75 13.25q0-3.75 3.75-3.75t3.75 3.75T14.5 17t-3.75-3.75");
}

</style>
