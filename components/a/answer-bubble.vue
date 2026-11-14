<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ht8uaob3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:answer-bubble" /></template>
<style>
.ht8uaob3d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.202 3.202Q2.25 4.154 2.25 5.5V14q0 3.25 3.25 3.25h.75v3.25q0 .149.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l3.781-3.78H18.5q1.346 0 2.298-.952T21.75 14V5.5q0-1.346-.952-2.298T18.5 2.25h-13q-1.346 0-2.298.952M9.75 13.5v-1.392q-1.5-1.304-1.5-3.358Q8.25 5 12 5t3.75 3.75q0 2.054-1.5 3.358V13.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146");
}

</style>
