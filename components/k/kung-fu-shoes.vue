<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q43fnlbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kung-fu-shoes" /></template>
<style>
.q43fnlbsd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 14.75v2.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H16q6.25 0 6.25-11.25q0-.125-.041-.243q-.04-.119-.117-.217q-.092-.118-.221-.192q-.13-.074-.278-.092t-.292.021t-.261.131Q14.814 11.25 10.5 11.25q-1.206 0-3.075-1.088Q5.857 9.25 5 9.25q-3.25 0-3.25 3.25zm0 0q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T2.5 14h17.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141q-.014-.072-.014-.146");
}

</style>
