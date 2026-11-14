<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz11plb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:black-friday" /></template>
<style>
.oz11plb3p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 1.75h7q.149 0 .287.057t.243.163l4 4q.106.105.163.243t.057.287v15q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-15q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-15q0-.149.057-.287t.163-.243l4-4q.105-.106.243-.163T8.5 1.75m3.5 2.5q-1.75 0-1.75 1.75T12 7.75T13.75 6T12 4.25M8.25 11q-1.5 0-1.5 1.5q0 .621.439 1.061q.44.439 1.061.439t1.061-.439q.439-.44.439-1.061q0-1.5-1.5-1.5m7.939 1.25l-.939-.939l-7.439 7.439l.939.939zm-.439 4.25q-1.5 0-1.5 1.5t1.5 1.5t1.5-1.5t-1.5-1.5");
}

</style>
