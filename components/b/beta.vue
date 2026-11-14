<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihjiu_eqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:beta" /></template>
<style>
.ihjiu_eqs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 21.5v-14q0-1.76 1.245-3.005T10.5 3.25t3.005 1.245T14.75 7.5q0 2.121-1.183 3.183q3.683 1.075 3.683 4.817q0 4.75-5.25 4.75q-2.581 0-4.25-1.075V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T7 22.25t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146m3-10.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q3.25 0 3.25-2.75T10.5 4.75T7.75 7.5v9.724Q9.136 18.75 12 18.75q3.75 0 3.75-3.25q0-3.75-5.75-3.75q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9.25 11");
}

</style>
