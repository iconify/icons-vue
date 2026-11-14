<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzmy8tb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:caricature" /></template>
<style>
.zzmy8tb9w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.843 4.282Q16.311 1.75 12 1.75T5.157 4.282Q2.75 6.689 2.75 10.5q0 4.24 3.107 8.037Q8.895 22.25 12 22.25t6.143-3.713Q21.25 14.74 21.25 10.5q0-3.811-2.407-6.218M5.75 10q0-2.75 2.75-2.75T11.25 10T8.5 12.75T5.75 10m9.75-2.75q2.75 0 2.75 2.75t-2.75 2.75T12.75 10t2.75-2.75m-3.944 8.5h1.694q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3q-.203 0-.378-.102q-.129-.075-.219-.194t-.128-.263t-.018-.292t.095-.277l1.75-3q.037-.064.086-.119t.108-.1t.125-.077t.138-.051t.145-.024q.074-.004.147.006t.143.034t.134.061t.119.086t.1.108t.077.125t.051.138t.024.145t-.006.147t-.034.143t-.061.134z");
}

</style>
