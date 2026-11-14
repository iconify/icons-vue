<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s48o7yggr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arc" /></template>
<style>
.s48o7yggr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 16q0-3.624 2.563-6.187T12 7.25t6.187 2.563q2.518 2.518 2.562 6.06q.011.063.011.127q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H20q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T19.25 16q0-3.003-2.123-5.127T12 8.75t-5.127 2.123q-2.081 2.082-2.122 5.01q.009.058.009.117q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T3.25 16");
}

</style>
