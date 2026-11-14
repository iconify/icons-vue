<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjlfzlb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:age-gate" /></template>
<style>
.vjlfzlb4x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M7.97 6.72q.105-.106.243-.163T8.5 6.5t.287.057t.243.163q.106.105.163.243t.057.287v9.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V9.061l-.47.469q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.106-.105-.163-.243T6 9t.057-.287t.163-.243zM18 9.5q0 1.442-.694 2.191q.944.808.944 2.559q0 3.25-3.25 3.25t-3.25-3.25q0-1.751.944-2.559Q12 10.942 12 9.5q0-3 3-3t3 3");
}

</style>
