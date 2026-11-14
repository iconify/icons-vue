<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu--_qbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arrow-up" /></template>
<style>
.lu--_qbgx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m5.22 9.72l6.249-6.25h.001q.105-.106.243-.163T12 3.25t.287.057t.243.163h.001l6.249 6.25q.106.105.163.243t.057.287t-.057.287t-.163.243q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-4.97-4.969V20q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T11.25 20V5.811L6.28 10.78q-.052.053-.113.094t-.13.069t-.141.043T5.75 11t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.106-.105-.163-.243T5 10.25t.057-.287t.163-.243");
}

</style>
