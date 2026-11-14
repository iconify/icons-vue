<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwvhxaczp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:filament-spool" /></template>
<style>
.nwvhxaczp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.777 3.012Q2.75 3.903 2.75 5.499v.002q0 1.596 3.027 2.487q.699.205 1.473.356v7.312q-.774.151-1.473.356q-3.027.891-3.027 2.487v.002q0 1.596 3.027 2.487q2.593.763 6.223.763t6.223-.763q3.029-.891 3.027-2.489q.002-1.596-3.027-2.487q-.699-.205-1.473-.356v-3.391q4 .17 4 2.235q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.518-5.5-3.736v-2.42q.774-.151 1.473-.356q3.029-.891 3.027-2.489q.002-1.596-3.027-2.487Q15.63 2.249 12 2.249t-6.223.763M15.25 11.5v3.925q-1.505-.176-3.25-.176t-3.25.176v-6.85q1.505.176 3.25.176t3.25-.176z");
}

</style>
