<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfru8ibfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cinema-camera-check" /></template>
<style>
.cfru8ibfv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 1.75Q2 1.75 2 5.25q0 1.737.862 2.612q-1.112.825-1.112 2.763v2.25q0 3.375 3.375 3.375h5.75q2.775 0 3.268-2.281q.102.038.21.07l2.001.6q1.082.325 1.989-.35t.907-1.805v-1.968q0-1.13-.907-1.805t-1.99-.35l-2 .6q-.178.053-.337.122q-.214-.6-.623-1.003Q14.5 7.219 14.5 5.25q0-3.5-3.5-3.5q-1.88 0-2.75 1.01q-.87-1.01-2.75-1.01m9.78 15.72l1.47 1.469l3.72-3.719q.052-.053.113-.094t.13-.069t.141-.043T21 15t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243l-4.25 4.25q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-2-2q-.053-.052-.094-.113t-.069-.13t-.043-.141T14 18t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.105-.106.243-.163t.287-.057t.287.057t.243.163");
}

</style>
