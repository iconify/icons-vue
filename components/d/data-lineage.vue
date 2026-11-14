<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlkpi5_ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:data-lineage" /></template>
<style>
.hlkpi5_ua {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.298 3.702Q20.346 2.75 19 2.75q-2.85 0-3.201 2.5H12q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T11.25 6v5.25H8.201Q7.85 8.75 5 8.75q-1.346 0-2.298.952T1.75 12q0 3.25 3.25 3.25q2.85 0 3.201-2.5h3.049V18q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h3.799q.351 2.5 3.201 2.5q3.25 0 3.25-3.25T19 14.75q-2.85 0-3.201 2.5H12.75V6.75h3.049q.351 2.5 3.201 2.5q3.25 0 3.25-3.25q0-1.346-.952-2.298");
}

</style>
