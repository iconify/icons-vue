<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-41ngxbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:concrete-pipe" /></template>
<style>
.a-41ngxbb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 11q0-3.099 1.27-5.322Q4.908 3.25 7 3.25h10q2.092 0 3.48 2.428Q21.75 7.901 21.75 11t-1.27 5.322Q19.092 18.75 17 18.75H7q-2.092 0-3.48-2.428Q2.25 14.099 2.25 11m8.23 5.322q-.297.52-.627.928H17q1.222 0 2.177-1.672Q20.25 13.7 20.25 11t-1.073-4.578Q18.222 4.75 17 4.75H9.853q.33.408.627.928Q11.75 7.901 11.75 11t-1.27 5.322M2.5 20h19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T2.5 20");
}

</style>
