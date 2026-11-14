<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ez3vdrb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:billy-can" /></template>
<style>
.ez3vdrb3c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.79 9.25h12.42q-.231-2.11-1.791-3.669Q14.589 3.75 12 3.75T7.581 5.581Q6.021 7.14 5.79 9.25m13.928 0H20q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.25v7.75q0 1.346-.952 2.298t-2.298.952h-9q-1.346 0-2.298-.952T4.25 18.5v-7.75H4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q3.25 10.074 3.25 10t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T4 9.25h.282Q4.52 6.52 6.52 4.52Q8.79 2.25 12 2.25t5.48 2.27q2 2 2.238 4.73M5.75 10.75v7.75q0 .725.513 1.237q.512.513 1.237.513h9q.725 0 1.237-.513q.513-.512.513-1.237v-7.75z");
}

</style>
