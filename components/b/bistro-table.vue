<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak0wenbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bistro-table" /></template>
<style>
.ak0wenbzl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 5.001v-.002q0-1.43 3.222-2.146Q8.189 2.249 12 2.249t6.528.604q3.224.717 3.222 2.146q.002 1.431-3.222 2.148q-2.446.543-5.778.598V17.5q0 2.75 4.75 2.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-4.085 0-5.5-1.816q-1.415 1.816-5.5 1.816q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.75 21q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q4.75 0 4.75-2.75V7.745q-3.332-.055-5.778-.598Q2.25 6.431 2.25 5.001");
}

</style>
