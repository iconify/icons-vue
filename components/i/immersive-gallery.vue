<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyluiabxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:immersive-gallery" /></template>
<style>
.vyluiabxn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-3.47 3.068-5.892Q7.805 3.75 12 3.75t7.182 2.358Q22.25 8.53 22.25 12t-3.068 5.892Q16.195 20.25 12 20.25t-7.182-2.358Q1.75 15.47 1.75 12m9.22-1.03l-3.5 3.5q-.106.105-.163.243T7.25 15t.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l2.97-2.969l2.97 2.969q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113l-3.5-3.5q-.105-.106-.243-.163t-.287-.057t-.287.057t-.243.163");
}

</style>
