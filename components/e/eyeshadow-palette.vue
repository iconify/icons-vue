<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fykx-yb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eyeshadow-palette" /></template>
<style>
.fykx-yb8u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.209 4.209Q1.5 6.919 1.5 10.75t2.709 6.541Q6.919 20 10.75 20t6.541-2.709Q20 14.581 20 10.75t-2.709-6.541Q14.581 1.5 10.75 1.5T4.209 4.209M7.75 5.5Q10 5.5 10 7.75T7.75 10T5.5 7.75T7.75 5.5m3.75 2.25q0-2.25 2.25-2.25T16 7.75T13.75 10T11.5 7.75M7.75 11.5q2.25 0 2.25 2.25T7.75 16T5.5 13.75t2.25-2.25m3.75 2.25q0-2.25 2.25-2.25T16 13.75T13.75 16t-2.25-2.25m3.97 7.47l5.75-5.75q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243T22.5 16t-.057.287t-.163.243l-5.75 5.75q-.105.106-.243.163T16 22.5t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113");
}

</style>
