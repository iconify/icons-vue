<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qeg_38bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:anklet" /></template>
<style>
.qeg_38bly {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 8.5q-.001 2.699 2.994 4.53q2.544 1.556 6.006 1.706v.306q-3 .354-3 3.708q0 3.75 3.75 3.75t3.75-3.75q0-3.354-3-3.708v-.306q3.462-.15 6.006-1.706q2.996-1.831 2.994-4.53q.002-2.699-2.994-4.53Q15.94 2.248 12 2.248T5.244 3.97Q2.249 5.801 2.25 8.5m9.76 9.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H12q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 18z");
}

</style>
