<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyjs3bcsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:commission-tier" /></template>
<style>
.xyjs3bcsg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.25 6q0-1.76 1.245-3.005T18.5 1.75t3.005 1.245T22.75 6q0 1.605-1.035 2.782q.058.017.112.043t.103.061t.093.076t.079.09t.063.102t.047.11t.028.117q.01.059.01.119v11q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V17q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h5.75V13.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T9 12.75h5.75V9.5q0-.06.01-.119q.009-.06.028-.117t.047-.11q.027-.054.063-.102t.079-.09t.093-.076t.103-.061t.112-.043Q14.25 7.605 14.25 6");
}

</style>
