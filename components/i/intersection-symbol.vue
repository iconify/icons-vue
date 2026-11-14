<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xceyfncuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:intersection-symbol" /></template>
<style>
.xceyfncuz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 20v-9q0-2.796 1.977-4.773T12 4.25t4.773 1.977T18.75 11v9q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T17.25 20v-9q0-2.175-1.538-3.712Q14.175 5.75 12 5.75T8.288 7.288Q6.75 8.825 6.75 11v9q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T6 20.75t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.25 20");
}

</style>
