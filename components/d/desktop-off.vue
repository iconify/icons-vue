<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg2z6yb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:desktop-off" /></template>
<style>
.wg2z6yb1l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.547 15.719L4.914 2.086q-.083-.084-.176-.157Q5.332 1.75 6 1.75h12q1.76 0 3.005 1.245T22.25 6v5.5q0 1.76-1.245 3.005q-1.047 1.047-2.458 1.214M4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094M2.086 4.914q-.084-.083-.157-.176Q1.75 5.332 1.75 6v5.5q0 1.76 1.245 3.005T6 15.75h6.922zm17 17l-4.164-4.164H5q-2.25 0-2.25 2.25T5 22.25h14q.255 0 .481-.029q-.217-.128-.395-.307");
}

</style>
