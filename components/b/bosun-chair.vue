<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0m_2vfsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bosun-chair" /></template>
<style>
.x0m_2vfsm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 21.5v-18q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q3.926 2.75 4 2.75h11q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v7.689l3.686 3.686Q20.75 15.28 20.75 17q0 2.25-2.25 2.25h-7q-2.25 0-2.25-2.25q0-1.72 1.314-2.125l3.686-3.686V4.25h-9.5V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T4 22.25t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146M15 12.561l-2.189 2.189h4.378z");
}

</style>
