<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvn26fbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:carpool-seats" /></template>
<style>
.qvn26fbca {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 16.5V13q0-1.444 1.192-1.697l2.346-7.04q.019-.056.046-.108t.062-.099t.076-.089q.042-.041.089-.075q.048-.035.1-.061q.053-.027.109-.045q.055-.018.113-.027T6 3.75h12q.059 0 .117.009t.113.027q.056.018.109.045q.052.026.1.061q.047.034.089.075t.076.089t.062.099t.046.108l2.346 7.04q1.192.253 1.192 1.697v3.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.509q-.08 1.083-.869 1.872q-.879.88-2.122.88t-2.122-.88q-.789-.789-.869-1.872H9.995Q9.872 20 7 20t-2.995-2.75H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146m7-10q-2.5 0-2.5 2.5t2.5 2.5t2.5-2.5t-2.5-2.5m4 2.5q0 2.5 2.5 2.5t2.5-2.5t-2.5-2.5t-2.5 2.5");
}

</style>
