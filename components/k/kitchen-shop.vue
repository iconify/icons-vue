<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcd8kwy6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kitchen-shop" /></template>
<style>
.xcd8kwy6m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.286 7.868l7.25-5.236q1.464-1.058 2.928 0l7.25 5.236q1.036.749 1.036 2.027v9.855q0 1.036-.732 1.768t-1.768.732H4.75q-1.036 0-1.768-.732T2.25 19.75V9.895q0-1.278 1.036-2.027m3.355 3.523Q5.25 12.782 5.25 14.75t1.391 3.359T10 19.5t3.359-1.391q1.118-1.118 1.337-2.609h3.554q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18.25 14h-3.554q-.219-1.491-1.337-2.609Q11.968 10 10 10t-3.359 1.391");
}

</style>
