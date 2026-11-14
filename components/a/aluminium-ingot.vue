<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbnfjzi9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:aluminium-ingot" /></template>
<style>
.wbnfjzi9z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.534 11.027l-.978 2.933q-.404 1.214.344 2.252t2.028 1.038h14.144q1.28 0 2.028-1.038t.344-2.252l-.978-2.933q.034.109.034.223q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H4.25q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141q-.014-.072-.014-.146q0-.114.034-.223m.009-.028q.039-.11.109-.202t.165-.16t.206-.102t.227-.035h15.5q.116 0 .227.035t.206.102t.165.16t.109.202l-.846-2.539q-.57-1.71-2.372-1.71H6.761q-1.802 0-2.372 1.71z");
}

</style>
