<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc_4aoixf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:guitar-body" /></template>
<style>
.sc_4aoixf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.318 14.338q.375-2.625 2.347-4.227q-.939-1.335-.914-3.049q.031-2.152 1.564-3.663Q9.847 1.888 12 1.888t3.685 1.511q1.533 1.511 1.564 3.663q.025 1.714-.914 3.049q1.972 1.602 2.347 4.227q.436 3.05-1.582 5.378T12 22.044q-3.081 0-5.1-2.328t-1.582-5.378M12 10.25q-2.75 0-2.75 2.75T12 15.75T14.75 13T12 10.25m3.25 7.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T14.5 17h-5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
