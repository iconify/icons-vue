<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcdbl_btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:landing-zone" /></template>
<style>
.qcdbl_btt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 10.5q-.001-2.513 3.021-4.192Q8.077 4.748 12 4.748t6.729 1.56q3.023 1.679 3.021 4.192q.002 2.513-3.021 4.192q-2.806 1.56-6.729 1.56t-6.729-1.56Q2.249 13.013 2.25 10.5m4.5 0q0 2.75 5.25 2.75t5.25-2.75T12 7.75T6.75 10.5m15.5 8.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T1.75 19t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
