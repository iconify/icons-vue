<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm_wdmb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eraser" /></template>
<style>
.pm_wdmb-a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.97 21.03l-4-4q-2.031-2.03 0-4.06l4-4q-.106.105-.163.243T6.75 9.5t.057.287t.163.243l7.5 7.5q.105.106.243.163t.287.057t.287-.057t.243-.163l-2.219 2.22H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H7.5q-.149 0-.287-.057t-.243-.163m8.56-3.5q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-7.5-7.5q-.052-.053-.113-.094t-.13-.069t-.141-.043T7.5 8.75t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094l5-5q2.03-2.031 4.06 0l4.5 4.5q.783.782.783 2.03t-.783 2.03z");
}

</style>
