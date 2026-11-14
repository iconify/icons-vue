<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyypkhgpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arrow-down" /></template>
<style>
.vyypkhgpl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.527 20.534l.003-.004l6.25-6.25q.106-.105.163-.243T19 13.75t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T18.25 13t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094l-4.97 4.969V4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 3.25 12 3.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T11.25 4v14.189L6.28 13.22q-.052-.053-.113-.094t-.13-.069t-.141-.043T5.75 13t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243T5 13.75t.057.287t.163.243l6.25 6.25q.105.106.243.163t.287.057q.148 0 .285-.056t.242-.16");
}

</style>
