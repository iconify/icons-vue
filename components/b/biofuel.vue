<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_zn9ea8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:biofuel" /></template>
<style>
.m_zn9ea8m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.75 14.5q0-4.796-7.202-12.512q-.017-.019-.036-.036q-.109-.102-.249-.154t-.289-.048q-.149.006-.285.067t-.237.171Q4.25 9.704 4.25 14.5q0 3.21 2.27 5.48T12 22.25t5.48-2.27t2.27-5.48m-11.5 3q0-6.75 6.75-6.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 6.75-6.75 6.75q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146");
}

</style>
