<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="woz8pe-vj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:evidence" /></template>
<style>
.woz8pe-vj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 7q0-2.75 2.75-2.75h4.5q.149 0 .287.057t.243.163l1.781 1.78H19q2.75 0 2.75 2.75v8q0 .961-.336 1.586l-.247-.248q.333-.85.333-1.838q0-2.071-1.464-3.536Q18.571 11.5 16.5 11.5t-3.536 1.464T11.5 16.5q0 1.873 1.198 3.25H5q-2.75 0-2.75-2.75zm14.25 5.75q-3.75 0-3.75 3.75t3.75 3.75q1.345 0 2.207-.482l1.763 1.762q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.762-1.763q.482-.862.482-2.207q0-3.75-3.75-3.75m0 6q-2.25 0-2.25-2.25t2.25-2.25t2.25 2.25t-2.25 2.25m-1-2.25q0 1 1 1t1-1t-1-1t-1 1");
}

</style>
