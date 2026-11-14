<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i80filbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dock-leveler" /></template>
<style>
.i80filbmj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 19.25h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V6q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h10q.227 0 .416.126l9 6q.124.083.207.207t.112.27q.03.146.001.293q-.029.146-.112.27q-.041.061-.093.114q-.052.052-.114.093q-.061.041-.129.07q-.068.028-.141.042t-.146.015q-.074 0-.147-.014q-.072-.015-.14-.043t-.13-.069L13.25 7.401V17.75h8.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014m-9.75-1.5v-11h-8.5v11z");
}

</style>
