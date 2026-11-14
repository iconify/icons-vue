<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfyn1cckt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:curved-window" /></template>
<style>
.wfyn1cckt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.274 2.285Q12 5.213 2.726 2.285q-.11-.035-.226-.035q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q1.75 2.926 1.75 3v12.5q0 .116.035.226q.045.142.141.256t.228.183t.281.082t.291-.032q9.274-2.928 18.548 0q.11.035.226.035q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V3q0-.116-.035-.226q-.022-.07-.058-.135q-.035-.065-.083-.121q-.047-.057-.105-.103t-.123-.08t-.136-.055t-.145-.027q-.074-.007-.147.001t-.144.031M12 16.25q3 0 3 3t-3 3t-3-3t3-3");
}

</style>
