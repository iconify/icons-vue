<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdiljbcxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:differential-diagnosis" /></template>
<style>
.sdiljbcxc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.254 5.294Q15.355 2.75 18 2.75q2.75 0 2.75 2.75T18 8.25q-2.095 0-2.594-1.596l-4.595 4.596H15.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4.689l4.595 4.596Q15.905 15.75 18 15.75q2.75 0 2.75 2.75T18 21.25q-2.645 0-2.746-2.544q-.123.044-.254.044q-.149 0-.287-.057t-.243-.163l-5.781-5.78H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 12.074 1.75 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h6.189l5.781-5.78q.105-.106.243-.163T15 5.25q.131 0 .254.044M16.25 12q0-2.75 2.75-2.75T21.75 12T19 14.75T16.25 12");
}

</style>
