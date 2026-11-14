<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcnc-uiek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:folding-machine" /></template>
<style>
.dcnc-uiek {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 5.75h-1.25V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 1.75H8q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v3.25H6q-1.76 0-3.005 1.245T1.75 10v1.5q0 1.76 1.245 3.005T6 15.75h1.25v5.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5q.149 0 .287-.057t.243-.163l3-3q.106-.105.163-.243t.057-.287v-2.75H18q1.76 0 3.005-1.245T22.25 11.5V10q0-1.76-1.245-3.005T18 5.75m-2.75 12H13q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v2.25h-3.5v-5h6.5zm-1.5 1.939v-.439h.439zm1.5-13.939h-6.5v-2.5h6.5z");
}

</style>
