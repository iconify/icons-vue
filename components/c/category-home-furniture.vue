<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fytz9lwzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-home-furniture" /></template>
<style>
.fytz9lwzw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.75 11.489q.573.238 1.048.713q.952.952.952 2.298t-.952 2.298q-.475.475-1.048.713V20q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T18.25 20v-2.25H5.75V20q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T5 20.75t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T4.25 20v-2.401q-2-.549-2-3.099q0-1.346.952-2.298q.475-.475 1.048-.713V9q0-2.75 2.75-2.75h10q2.75 0 2.75 2.75zm-14-.239h12.5V9q0-1.25-1.25-1.25H7Q5.75 7.75 5.75 9z");
}

</style>
