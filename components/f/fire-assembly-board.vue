<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpqjogbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fire-assembly-board" /></template>
<style>
.mpqjogbmo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 1.75h-11q-1.76 0-3.005 1.245T2.25 6v6.5q0 1.76 1.245 3.005T6.5 16.75h4.75v4H8.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h7q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-2.75v-4h4.75q1.76 0 3.005-1.245T21.75 12.5V6q0-1.76-1.245-3.005T17.5 1.75m-5.002 3.189Q15.75 7.83 15.75 10.25Q15.75 14 12 14t-3.75-3.75q0-2.42 3.252-5.311q.051-.045.109-.08t.122-.06t.132-.037T12 4.75t.135.012q.068.013.132.037q.063.024.122.06t.109.08");
}

</style>
