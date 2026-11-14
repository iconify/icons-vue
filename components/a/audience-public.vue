<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="taar4fjhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:audience-public" /></template>
<style>
.taar4fjhv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 11.999q0-4.245 3.002-7.247T12 1.75q-2.155 0-3.52 3.241q-1.116 2.651-1.219 6.259H2.5q-.074 0-.146.014q-.073.015-.141.043t-.129.069t-.114.093q-.052.052-.093.114q-.041.061-.07.129q-.028.068-.042.141t-.015.146m0 .002q0 4.245 3.002 7.247T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75q2.155 0 3.52 3.241q1.116 2.651 1.219 6.259H21.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4.761q-.103 3.608-1.219 6.259Q14.155 22.25 12 22.25t-3.52-3.241q-1.116-2.651-1.219-6.259H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.129-.069t-.114-.093q-.052-.052-.093-.114q-.041-.061-.07-.129q-.028-.068-.042-.141t-.015-.146");
}

</style>
