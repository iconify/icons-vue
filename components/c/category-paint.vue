<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcbi861kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-paint" /></template>
<style>
.gcbi861kv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.625 2.75h10.75q3.375 0 3.375 3.375V12q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-6q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9.25 21v-7.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h1.25v-2.5H6.625q-3.375 0-3.375-3.375v-.75q0-3.375 3.375-3.375m6.125 8.5v-1h4.625q1.125 0 1.875-.375v1.375zm-2 3v6h2.5v-6z");
}

</style>
