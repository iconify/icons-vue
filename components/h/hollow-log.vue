<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfulzacfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hollow-log" /></template>
<style>
.cfulzacfv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 4h12.001q2.058.001 3.451 2.091q1.298 1.947 1.298 4.659t-1.298 4.659Q19.558 17.5 17.5 17.5h-12q-3.75 0-3.75-6.75T5.5 4m0 1.5h8.99q-.229.271-.442.591q-1.298 1.947-1.298 4.659t1.298 4.659q.213.32.442.591H5.5q-2.25 0-2.25-5.25T5.5 5.5m12 1.5q-2.25 0-2.25 3.75t2.25 3.75t2.25-3.75T17.5 7m4 11.75h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
