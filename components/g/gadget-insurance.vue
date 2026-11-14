<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b54c7qgwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gadget-insurance" /></template>
<style>
.b54c7qgwn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.412 21.261q-.653.239-1.349.239H8.438q-.193 0-.386-.019q-.192-.019-.382-.057q-.19-.037-.375-.094q-.185-.056-.364-.13q-.178-.074-.349-.165t-.332-.198t-.31-.231q-.149-.122-.286-.259t-.26-.286t-.23-.311q-.107-.16-.199-.331q-.091-.171-.165-.349q-.074-.179-.13-.364t-.094-.375t-.057-.382t-.019-.386V6.438q0-.193.019-.386t.057-.382q.037-.19.094-.375q.056-.185.13-.364t.165-.349q.091-.171.199-.332q.107-.161.23-.31q.123-.15.259-.287q.137-.136.287-.259t.31-.23q.161-.108.332-.199q.17-.091.349-.165t.364-.13t.375-.094q.189-.038.382-.057t.386-.019h3.625q.193 0 .386.019q.192.019.382.057t.375.094t.364.13t.349.165t.331.199t.311.23q.149.123.286.26t.259.286t.231.31q.107.161.198.332t.165.349q.074.179.13.364t.094.375t.057.382q.019.193.019.386v6.448M9 5.5h2.5m7 9.5l3 1v2.5c0 1.75-1.25 2.75-3 3.5c-1.75-.75-3-1.75-3-3.5V16Z");
}

</style>
