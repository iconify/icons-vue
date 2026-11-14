<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t66t_xblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fabric-roll" /></template>
<style>
.t66t_xblb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 10q0-3.003 2.123-5.127T9 2.75t5.127 2.123Q16.25 6.997 16.25 10t-2.123 5.127q-.339.338-.7.623H20q2.25 0 2.25 2.25v2.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V18q0-.75-.75-.75H9q-3.003 0-5.127-2.123T1.75 10m4.5 0q0-2.75 2.75-2.75T11.75 10T9 12.75T6.25 10");
}

</style>
