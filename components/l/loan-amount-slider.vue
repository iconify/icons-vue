<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w32zh_c6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:loan-amount-slider" /></template>
<style>
.w32zh_c6y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.81 11.25q.214-1.284 1.185-2.255Q13.24 7.75 15 7.75t3.005 1.245q.971.971 1.185 2.255H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.81q-.214 1.284-1.185 2.255Q16.76 16.25 15 16.25t-3.005-1.245q-.971-.971-1.185-2.255H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q2.25 12.074 2.25 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T3 11.25z");
}

</style>
