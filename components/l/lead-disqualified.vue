<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmq9qpblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lead-disqualified" /></template>
<style>
.zmq9qpblj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094m4.431 2.663l5.906 5.906q.334-.23.638-.534Q16.25 9.76 16.25 8t-1.245-3.005T12 3.75T8.995 4.995q-.304.304-.534.638m9.961 15.617l-7.691-7.691q-2.608.253-4.504 1.576Q3.75 16.863 3.75 19.5q0 1.75 1.75 1.75z");
}

</style>
