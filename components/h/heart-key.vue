<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_1suzb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heart-key" /></template>
<style>
.x_1suzb6g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m9.086 18.719l4.774-5.969h3.64v2.75q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T19 15.5v-2.75h1.5V15q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T22 15v-3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-7.39L9.086 5.281q-.105-.13-.256-.204q-3.509-1.721-5.873 1.39Q.793 9.314 2.783 12q-1.99 2.686.174 5.533q2.364 3.111 5.873 1.39q.151-.074.256-.204");
}

</style>
