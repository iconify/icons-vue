<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5gksrt7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:infra-lint" /></template>
<style>
.t5gksrt7x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 1.75h14q2.75 0 2.75 2.75T19 7.25H5q-2.75 0-2.75-2.75q0-1.139.805-1.945Q3.861 1.75 5 1.75M19 8.5H5q-1.139 0-1.945.805q-.805.806-.805 1.945Q2.25 14 5 14h14q2.75 0 2.75-2.75T19 8.5m-3.72 8.97l1.47 1.469l3.72-3.719q.052-.053.113-.094t.13-.069t.141-.043T21 15t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243l-4.25 4.25q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-2-2q-.053-.052-.094-.113t-.069-.13t-.043-.141T14 18t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.105-.106.243-.163t.287-.057t.287.057t.243.163M5 15.25h4.5q2.75 0 2.75 2.75T9.5 20.75H5q-2.75 0-2.75-2.75T5 15.25");
}

</style>
