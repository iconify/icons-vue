<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwcawlv4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cargo-hold" /></template>
<style>
.cwcawlv4v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 21v-9.5q.001-4.038 2.857-6.892Q7.962 1.753 12 1.753t6.893 2.855q2.856 2.854 2.857 6.892V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.25 21");
}

</style>
