<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eeooi175t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:floor-lamp" /></template>
<style>
.eeooi175t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.261 2.25h5.478q1.802 0 2.372 1.71l.833 2.5q.404 1.214-.344 2.252T15.572 9.75H12.75v10.5H16q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.25 21q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T8 20.25h3.25V9.75H8.428q-1.28 0-2.028-1.038T6.056 6.46l.833-2.5q.57-1.71 2.372-1.71");
}

</style>
