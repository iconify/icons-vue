<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sciufcbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:billet" /></template>
<style>
.sciufcbye {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 12v6.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h6.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-5.75H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q2.25 12.074 2.25 12m8 .412V18.5q0 .095-.023.186q-.024.092-.069.175t-.11.152t-.145.119l11-6.999q.079-.051.144-.12t.11-.152t.069-.175t.024-.186V5q0 .095-.024.186q-.023.092-.069.175q-.045.083-.11.152t-.144.12zM20.5 4.25H14q-.218 0-.403.117l-10.999 7q.184-.117.402-.117h6.282l10.815-6.883q.184-.117.403-.117");
}

</style>
