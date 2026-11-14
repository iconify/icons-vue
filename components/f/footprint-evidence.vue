<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je-ribcqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:footprint-evidence" /></template>
<style>
.je-ribcqg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 1.75q5.25 0 5.25 6.25q0 1.565-.955 3.753q-.545 1.249-.545 1.747q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.498-.545-1.747Q3.75 9.565 3.75 8q0-6.25 5.25-6.25m5.785 17.165l.942-3.5q.448-1.666 2.173-1.665h.7q1.725-.001 2.173 1.665l.942 3.5q.289 1.072-.386 1.953q-.676.882-1.786.882h-2.586q-1.11 0-1.786-.882q-.675-.881-.386-1.953M12.75 18.5q0-3.25-3.25-3.25h-1q-3.25 0-3.25 3.25q0 1.346.952 2.298t2.298.952h1q1.346 0 2.298-.952t.952-2.298");
}

</style>
