<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt_yqsyxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:garden-trug" /></template>
<style>
.pt_yqsyxf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.75 11.25h1.165q1.327 0 2.07 1.098q.744 1.099.251 2.331l-1.6 4q-.628 1.571-2.321 1.571H6.685q-1.693 0-2.321-1.571l-1.06-2.65q.042.104.112.192q.071.087.164.15t.2.096t.22.033h16q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 15H4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146q0 .144.054.278l-.54-1.349q-.493-1.232.251-2.331q.743-1.098 2.07-1.098H6.25V7.5q0-2.382 1.684-4.066T12 1.75t4.066 1.684T17.75 7.5zm-10 0V7.5q0-1.76 1.245-3.005T12 3.25t3.005 1.245T16.25 7.5v3.75z");
}

</style>
