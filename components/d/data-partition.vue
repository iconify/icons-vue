<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muzaeeznb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:data-partition" /></template>
<style>
.muzaeeznb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 18.5v-13q0-1.139.805-1.945Q3.861 2.75 5 2.75h14q2.75 0 2.75 2.75v13q0 2.75-2.75 2.75h-2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V8.75h-1.5V20.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V8.75h-1.5V20.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H5q-2.75 0-2.75-2.75m15-3.5v4.75H19q1.25 0 1.25-1.25V15zm3-1.5V8.75h-3v4.75zm-13.5 0V8.75h-3v4.75zm6-4.75v4.75h-1.5V8.75zm-9 6.25v3.5q0 1.25 1.25 1.25h1.75V15zm9 0h-1.5v4.75h1.5z");
}

</style>
