<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-bn-l1_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:food-storage-box" /></template>
<style>
.e-bn-l1_u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.25 3.25q-3 0-3 3v11.5q0 1.243.879 2.121q.878.879 2.121.879q3 0 3-3V6.25q0-3-3-3M6 7.25h5q1.76 0 3.005 1.245T15.25 11.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-12q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146q0-1.76 1.245-3.005T6 7.25M1.75 11.5q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h12q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v5q0 1.76-1.245 3.005T11 20.75H6q-1.76 0-3.005-1.245T1.75 16.5z");
}

</style>
