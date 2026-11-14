<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt9exwbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gantt-shift" /></template>
<style>
.zt9exwbgx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 4.25h-6.5q-1.243 0-2.121.879q-.879.878-.879 2.121q0 3 3 3h6.5q3 0 3-3t-3-3m10.78 2.47l-2.25-2.25q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243T18.5 5t.057.287t.163.243l.969.97H16.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T16.5 8h3.189l-.969.97q-.106.105-.163.243T18.5 9.5t.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l2.25-2.25q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243m-11.78 7.03h9q3 0 3 3t-3 3h-9q-3 0-3-3t3-3");
}

</style>
