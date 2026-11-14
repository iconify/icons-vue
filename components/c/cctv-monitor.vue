<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oeoz-pn_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cctv-monitor" /></template>
<style>
.oeoz-pn_d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 2.75h10.25q2.123 0 3.624 1.501t1.501 3.624v4.25q0 2.123-1.501 3.624t-3.624 1.501H12.75v2.5H16q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T8 19.75h3.25v-2.5H6.875q-2.123 0-3.624-1.501T1.75 12.125v-4.25q0-2.123 1.501-3.624T6.875 2.75m1.943 4.068Q7.5 8.136 7.5 10t1.318 3.182T12 14.5t3.182-1.318T16.5 10t-1.318-3.182T12 5.5T8.818 6.818");
}

</style>
