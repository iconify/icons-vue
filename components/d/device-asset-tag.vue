<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpmkd7tkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:device-asset-tag" /></template>
<style>
.hpmkd7tkt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.625 4.25h5.288q1.398 0 2.386.989l6.375 6.375q2.386 2.386 0 4.772L16.21 19.85q-2.159 2.161-4.524.226l-8.198-6.708Q2.25 12.356 2.25 10.756V7.625q0-3.375 3.375-3.375M7.5 8.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014zm6.092 2.366h-.001q-.659-.66-1.591-.66t-1.592.66l-.706.708q-1.591 1.59 0 3.181l.707.707q.659.66 1.591.66t1.591-.66l.707-.707q1.591-1.591.001-3.181z");
}

</style>
