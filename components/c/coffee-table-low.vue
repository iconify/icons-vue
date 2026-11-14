<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq1n-ub1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:coffee-table-low" /></template>
<style>
.qq1n-ub1i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 8.5q0-1.973 3.273-3.179Q7.931 4.25 12 4.25t6.977 1.071Q22.25 6.527 22.25 8.5t-3.273 3.179q-2.637.971-6.227 1.062v5.509h3.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.75 19q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h3.75v-5.509q-3.59-.091-6.227-1.062Q1.75 10.473 1.75 8.5");
}

</style>
