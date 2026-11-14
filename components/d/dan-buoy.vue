<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbsdp8bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dan-buoy" /></template>
<style>
.wbsdp8bfp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 13.773V7.448q.744.281 1.557-.032l1.212-.466q1.34-.514 1.34-1.95t-1.34-1.95l-1.212-.466q-.814-.313-1.557-.032V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 1.75 12 1.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v11.273q-2.213.137-3.871 1.104Q5.25 16.119 5.25 18t2.129 3.123Q9.312 22.25 12 22.25t4.621-1.127Q18.75 19.881 18.75 18t-2.129-3.123q-1.658-.967-3.871-1.104");
}

</style>
