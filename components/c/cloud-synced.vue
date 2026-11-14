<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhf2ynbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloud-synced" /></template>
<style>
.yhf2ynbxi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 14.75q-1.968 0-3.359-1.391T1.75 10t1.391-3.359q1.216-1.215 2.871-1.369Q7.819 1.648 12 1.648t5.988 3.624q1.655.154 2.871 1.369Q22.25 8.032 22.25 10t-1.391 3.359q-.315.315-.659.558q-.263.115-.483.299q-.998.534-2.217.534zm8.78 2.72l1.47 1.469l3.72-3.719q.052-.053.113-.094t.13-.069t.141-.043T21 15t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243l-4.25 4.25q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-2-2q-.053-.052-.094-.113t-.069-.13t-.043-.141T14 18t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.105-.106.243-.163t.287-.057t.287.057t.243.163");
}

</style>
