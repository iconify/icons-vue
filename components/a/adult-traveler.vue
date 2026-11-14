<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfb_mfbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:adult-traveler" /></template>
<style>
.yfb_mfbwq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.288 3.288Q6.75 4.825 6.75 7t1.538 3.712Q9.825 12.25 12 12.25t3.712-1.538Q17.25 9.175 17.25 7t-1.538-3.712Q14.175 1.75 12 1.75T8.288 3.288M2.75 21.5V20q0-2.382 1.684-4.066T8.5 14.25h7q2.382 0 4.066 1.684T21.25 20v1.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V20q0-1.76-1.245-3.005T15.5 15.75h-7q-1.76 0-3.005 1.245T4.25 20v1.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146");
}

</style>
