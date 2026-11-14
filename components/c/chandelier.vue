<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avcrpsbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chandelier" /></template>
<style>
.avcrpsbba {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 1.75H9q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043q.072.014.146.014h2.25v11H7.5q-2.15 0-2.246-2.055Q7.5 11.846 7.5 9.25q0-3-3-3q-1.243 0-2.121.879Q1.5 8.007 1.5 9.25q0 2.6 2.253 2.947Q3.85 15.75 7.5 15.75h1.757Q9 16.371 9 17.25q0 3 3 3t3-3q0-.879-.257-1.5H16.5q3.65 0 3.747-3.553Q22.5 11.85 22.5 9.25q0-3-3-3t-3 3q0 2.596 2.246 2.945q-.096 2.055-2.246 2.055h-3.75v-11H15q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q15.074 1.75 15 1.75");
}

</style>
