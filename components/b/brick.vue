<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp0pd85ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:brick" /></template>
<style>
.xp0pd85ez {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 11v7q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h14q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T15.75 18v-6.25H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 11.074 1.75 11m15.5.311V18q0 .149-.057.287t-.163.243l5-5q.106-.105.163-.243T22.25 13V6q0 .149-.057.287t-.163.243zM21.5 5.25h-15q-.084 0-.167.019q-.082.018-.158.055t-.142.089t-.119.118l-3.999 5q.052-.066.118-.118q.066-.053.142-.089q.076-.037.158-.055q.083-.019.167-.019h13.689l4.781-4.78q.105-.106.243-.163q.137-.057.287-.057");
}

</style>
