<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htwe6cwci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cappuccino-cup" /></template>
<style>
.htwe6cwci {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.918 9.027Q7.393 4.75 11 4.75t7.08 4.275l.002.002q.082.1.125.222t.043.251v.25h.25q3 0 3 3t-3 3h-2.407q-1.339 1-3.093 1H9q-2.175 0-3.712-1.538Q3.75 13.675 3.75 11.5v-2q0-.129.043-.251t.125-.222M11 6.25q-2.371 0-4.83 2.5h9.66q-2.459-2.5-4.83-2.5m6.486 8H18.5q1.5 0 1.5-1.5t-1.5-1.5h-.25v.25q0 1.533-.764 2.75m-14.986 4h19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 19t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
