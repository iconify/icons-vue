<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyimbowba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:clone-stamp" /></template>
<style>
.oyimbowba {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.995 2.995Q7.75 4.24 7.75 6t1.245 3.005q.293.293.614.517l-1.14 3.228H6q-1.139 0-1.945.805q-.805.806-.805 1.945q0 2.75 2.75 2.75h12q2.75 0 2.75-2.75T18 12.75h-2.469l-1.14-3.228q.321-.224.614-.517Q16.25 7.76 16.25 6t-1.245-3.005T12 1.75T8.995 2.995m1.065 9.755h3.88l-.923-2.614q-.485.114-1.017.114t-1.017-.114zm-4.56 7h13q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-13q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
