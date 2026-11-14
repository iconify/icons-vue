<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed4tejk-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chemical-label" /></template>
<style>
.ed4tejk-x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 1.75h-4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v4.708q-3.38 1.234-4.581 4.736q-1.294 3.773 1.024 7.018Q8.011 22.208 12 22.208t6.307-3.246t1.024-7.018Q18.13 8.442 14.75 7.208V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q14.074 1.75 14 1.75m-.409 9.781l1.378 1.378q.66.659.66 1.591t-.66 1.591l-1.378 1.378q-.659.66-1.591.66t-1.591-.66l-1.378-1.378q-.66-.659-.66-1.591t.66-1.591l1.378-1.378q.659-.66 1.591-.66t1.591.66");
}

</style>
