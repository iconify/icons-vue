<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgdgjhzmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:age-limit-18" /></template>
<style>
.sgdgjhzmz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M8.47 7.47q.105-.106.243-.163T9 7.25t.287.057t.243.163t.163.243T9.75 8v8q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T9 16.75t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.25 16V9.811l-.22.219q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.106-.105-.163-.243T6.75 9.5t.057-.287t.163-.243zm3.03 2.529q0-1.035.732-1.767q.732-.733 1.768-.733t1.768.733q.733.732.732 1.767q.001.87-.515 1.526Q17 12.255 17 14q0 3-3 3t-3-3q0-1.745 1.015-2.475q-.515-.656-.515-1.524z");
}

</style>
