<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2jepubtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:child-scale" /></template>
<style>
.e2jepubtb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 2.25h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q1.75 2.926 1.75 3q0 6.98 9.5 7.24v1.51H7q-1.76 0-3.005 1.245T2.75 16v2q0 1.76 1.245 3.005T7 22.25h10q1.76 0 3.005-1.245T21.25 18v-2q0-1.76-1.245-3.005T17 11.75h-4.25v-1.51q9.5-.26 9.5-7.24q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014M9.75 17q0-2.25 2.25-2.25T14.25 17T12 19.25T9.75 17");
}

</style>
