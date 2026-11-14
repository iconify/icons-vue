<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxyc2bcst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lawsuit" /></template>
<style>
.dxyc2bcst {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.934 7.47L8.47 3.934q.952-.952 2.298-.952t2.298.952t.952 2.298t-.952 2.298l-1.237 1.238l7.701 7.702q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-7.702-7.701l-1.238 1.237q-.952.952-2.298.952t-2.298-.952t-.952-2.298t.952-2.298m-.184 9.78h6.5q2.5 0 2.5 2.5q0 1.036-.732 1.768t-1.768.732h-6.5q-1.036 0-1.768-.732T2.25 19.75q0-2.5 2.5-2.5");
}

</style>
