<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj2h2jbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dj-controller" /></template>
<style>
.pj2h2jbpa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.5 5.75h-13q-1.76 0-3.005 1.245T1.25 10v4q0 1.76 1.245 3.005T5.5 18.25h13q1.76 0 3.005-1.245T22.75 14v-4q0-1.76-1.245-3.005T18.5 5.75M4 12q0-3.5 3.5-3.5T11 12t-3.5 3.5T4 12m8 3.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-5.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 8.5t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v5.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T12 15.5m4.5-7Q20 8.5 20 12t-3.5 3.5T13 12t3.5-3.5");
}

</style>
