<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdy-vbb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cricketer-bowling" /></template>
<style>
.pdy-vbb-m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.25 5q0-1.75.875-2.625T18.75 1.5q3.5 0 3.5 3.5t-3.5 3.5q-.122 0-.241-.004l-3.313 8.283q-.054.135-.155.24q-.101.106-.234.165q1.443 1.713 1.443 4.316q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-5.25-5.75-5.25T3.25 21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-3.217 2.204-5.074Q5.945 14.75 9 14.75q2.87 0 4.801 1.479l.003-.008l3.207-8.017Q15.25 7.482 15.25 5M9 4.75q-3.75 0-3.75 3.75T9 12.25t3.75-3.75T9 4.75");
}

</style>
