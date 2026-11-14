<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp7sxybyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:golf-green" /></template>
<style>
.jp7sxybyz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 12.761q-3.608.103-6.259 1.219Q1.75 15.345 1.75 17.5t3.241 3.52Q7.914 22.25 12 22.25t7.009-1.23q3.241-1.365 3.241-3.52t-3.241-3.52q-2.651-1.116-6.259-1.219V8.368q.783.297 1.626-.059l1.166-.493q1.369-.579 1.369-2.066t-1.369-2.066l-1.166-.493q-.843-.356-1.626-.059V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 2.25 12 2.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T11.25 3z");
}

</style>
