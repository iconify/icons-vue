<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipshoqb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:database-connection" /></template>
<style>
.ipshoqb4m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 4.5Q1.75 2 7 2t5.25 2.5v6q0 2.315-4.5 2.486v3.264h4v-2.751q0-1.237 1.795-1.936q1.45-.564 3.455-.564t3.455.564q1.797.699 1.795 1.936v6.002q-.003 2.498-5.25 2.498T11.75 19.5v-1.75H7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.25 17v-4.014q-4.5-.171-4.5-2.486zm5.249 7h.002q3.749 0 3.749-1V6.458Q9.444 7 7 7t-3.75-.542V10.5q0 1 3.749 1M13.25 17v2.5q.001.999 3.75.999t3.75-1v-4.186q-.141.064-.295.124q-1.45.564-3.455.564t-3.455-.564q-.154-.06-.295-.124z");
}

</style>
