<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oezzl2nfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:living-room" /></template>
<style>
.oezzl2nfb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.75 10.523q2 .738 2 3.477q0 3.354-3 3.708V20q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T17.25 20v-2.25H6.75V20q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T6 20.75t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.25 20v-2.292q-3-.354-3-3.708q0-2.739 2-3.477V8q0-2.75 2.75-2.75h10q2.75 0 2.75 2.75zm-14-.269q.123-.004.25-.004h12q.127 0 .25.004V8q0-1.25-1.25-1.25H7Q5.75 6.75 5.75 8z");
}

</style>
