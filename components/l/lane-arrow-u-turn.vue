<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojnrik_8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lane-arrow-u-turn" /></template>
<style>
.ojnrik_8n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.25 9v12.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V9q0-2.382-1.684-4.066T13 3.25T8.934 4.934T7.25 9v7.689L5.03 14.47q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243T3.75 15t.057.287t.163.243l3.5 3.5q.105.106.243.163T8 19.25q.148 0 .285-.056t.242-.16l.003-.004l3.5-3.5q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094l-2.22 2.219V9q0-1.76 1.245-3.005T13 4.75t3.005 1.245T17.25 9");
}

</style>
