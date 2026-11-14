<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_nspqfzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:coffee-scoop" /></template>
<style>
.e_nspqfzb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21 6H11q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v2.689L2.97 16.72q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163T3.5 18t.287-.057t.243-.163l6.266-6.265q.231 1.894 1.638 3.301Q13.618 16.5 16 16.5t4.066-1.684t1.684-4.066v-4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 6");
}

</style>
