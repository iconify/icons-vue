<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcsq2ybjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:component-property" /></template>
<style>
.kcsq2ybjq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.386 3.826l3.788 3.788q2.386 2.386 0 4.772l-3.788 3.788q-2.386 2.386-4.772 0l-3.788-3.788Q1.44 10 3.826 7.614l3.788-3.788q2.386-2.386 4.772 0M17 15.25q2.25 0 2.25 2.25v.75h2.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-2.25v.75q0 2.25-2.25 2.25t-2.25-2.25v-.75H12.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T11.75 19t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h2.25v-.75q0-2.25 2.25-2.25m.75 2.25v.75h-1.5v-.75q0-.75.75-.75t.75.75m-1.5 3v-.75h1.5v.75q0 .75-.75.75t-.75-.75");
}

</style>
