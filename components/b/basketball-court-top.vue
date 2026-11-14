<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm2owkbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:basketball-court-top" /></template>
<style>
.dm2owkbsp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.125 4.75H12q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v3.045Q8.5 8.898 8.5 12t2.75 3.455V18.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H5.125q-3.375 0-3.375-3.375V13.5q0 2.25 2.25 2.25h1q2.25 0 2.25-2.25v-3q0-2.25-2.25-2.25H4q-2.25 0-2.25 2.25V8.125q0-3.375 3.375-3.375M22.25 13.5v2.375q0 3.375-3.375 3.375H12q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3.045Q15.5 15.102 15.5 12t-2.75-3.455V5.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 4.75h6.875q3.375 0 3.375 3.375V10.5q0-2.25-2.25-2.25h-1q-2.25 0-2.25 2.25v3q0 2.25 2.25 2.25h1q2.25 0 2.25-2.25");
}

</style>
