<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz-5-ln5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:balaclava" /></template>
<style>
.iz-5-ln5t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 9v5.25q0 1.71.929 2.822l-2.014 1.007Q2.25 19.036 2.25 21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h18q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-2.464-1.915-3.421l-2.014-1.007q.929-1.112.929-2.822V9q0-2.796-1.977-4.773T12 2.25T7.227 4.227T5.25 9m3 1.625q0-2.375 2.375-2.375h2.75q2.375 0 2.375 2.375T13.375 13h-2.75Q8.25 13 8.25 10.625");
}

</style>
