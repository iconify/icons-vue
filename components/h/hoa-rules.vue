<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snn6k2-ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hoa-rules" /></template>
<style>
.snn6k2-ie {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 19.25V5q0-1.346.952-2.298T7 1.75h12.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146V17q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H6.75q-1.498.001-1.498 1.5t1.499 1.5H19.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H6.749q-2.972-.002-2.997-2.948zm3-3h12v-13H7q-.725 0-1.237.513Q5.25 4.275 5.25 5v11.509q.621-.258 1.5-.259M14.5 4h-4Q8.25 4 8.25 6.25v6.25q0 .932.659 1.591t1.591.659h4q.932 0 1.591-.659t.659-1.591V6.25Q16.75 4 14.5 4");
}

</style>
