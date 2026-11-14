<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqzuy6b5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chart-bar-diverging" /></template>
<style>
.wqzuy6b5a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 2.5v.753q.061-.003.125-.003h5.75q1.625 0 1.625 1.625T18.625 6.5h-5.75q-.064 0-.125-.003v6.256q.061-.003.125-.003h3.25q1.625 0 1.625 1.625T16.125 16h-3.25q-.064 0-.125-.003V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-.754q-.062.004-.125.004h-6.75q-1.625 0-1.625-1.625T4.375 17.5h6.75q.063 0 .125.004v-6.258q-.062.004-.125.004h-4.75q-.673 0-1.149-.476T4.75 9.625t.476-1.149T6.375 8h4.75q.063 0 .125.004V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
