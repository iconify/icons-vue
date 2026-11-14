<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkpt7obvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:auto-mode" /></template>
<style>
.bkpt7obvb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 3.25Q2.25 3.25 2.25 6q0 2.345 2 2.69V20.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-5.75h5.5v5.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-5.75H19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V8.69q2-.345 2-2.69q0-2.75-2.75-2.75T16.25 6q0 2.345 2 2.69v4.56h-5.5V8.69q2-.345 2-2.69q0-2.75-2.75-2.75T9.25 6q0 2.345 2 2.69v4.56h-5.5V8.69q2-.345 2-2.69q0-2.75-2.75-2.75");
}

</style>
