<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trf_yxpqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:core-drill-rig" /></template>
<style>
.trf_yxpqt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 21.75q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-3.683L12.722 2.295q-.027-.092-.075-.175q-.049-.082-.117-.15t-.15-.117q-.083-.048-.175-.075q-.101-.028-.205-.028h-.002q-.06 0-.12.01t-.118.029q-.057.02-.111.048q-.053.029-.102.065t-.09.081t-.076.094t-.06.105t-.043.113L6.183 20.25H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T1.75 21t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014zm-8.75-1.5h3.508L14.2 13h-1.45zM11.25 13v7.25H7.742L9.8 13zm1.5-1.5V7.89l1.024 3.61zm-1.5-3.61v3.61h-1.024z");
}

</style>
