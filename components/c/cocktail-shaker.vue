<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyl770bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cocktail-shaker" /></template>
<style>
.vyl770bus {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.5 1.75h-1q-2 0-2 2q0 .268.036.5q-1.556.001-2.103 1.46l-.385 1.026q-.371.988.136 1.867q-.312.193-.576.493q-.746.845-.606 1.964l1.062 8.5q.274 2.191 2.481 2.19h4.91q2.207.001 2.481-2.19l1.062-8.5q.14-1.119-.606-1.964q-.264-.299-.576-.493q.507-.879.136-1.866l-.385-1.027q-.547-1.459-2.103-1.46q.036-.232.036-.5q0-2-2-2m4.25 10.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-9.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.5 13t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
