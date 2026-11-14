<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nke5vubkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:atm-armored-van" /></template>
<style>
.nke5vubkz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 17V9q0-1.139.805-1.945q.806-.805 1.945-.805H14q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2.25H18q.134 0 .26.047q.126.046.228.134l3.5 3q.125.106.193.256q.069.149.069.313v4q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-2.067q.067.342.067.75q0 2.5-2.5 2.5t-2.5-2.5q0-.408.067-.75H9.393q.107.353.107.75q.001 1.036-.732 1.768q-.732.733-1.768.733t-1.768-.733Q4.5 19.536 4.5 18.5q0-.397.108-.75H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 17M7.5 9.25q-2.25 0-2.25 2.25v.5q0 2.25 2.25 2.25H9q2.25 0 2.25-2.25v-.5q0-2.25-2.25-2.25zm13.25 7v-2.905l-3.027-2.595H14.75v5.5h.919Q16.209 16 17 16t1.331.25z");
}

</style>
