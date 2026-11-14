<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knrkzaclb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camp-wagon" /></template>
<style>
.knrkzaclb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m21.03 3.97l-1.25-1.25q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243t-.057.287t.057.287t.163.243l.719.72l-2.842 2.842q-.565-2.092-3.222-2.092h-7.75q-3.375 0-3.375 3.375v3.75q0 1.398.989 2.386q.04.041.081.079q-1.07.795-1.07 2.66q0 3.25 3.25 3.25t3.25-3.25q0-1.042-.334-1.75h2.168q-.334.708-.334 1.75q0 3.25 3.25 3.25t3.25-3.25q0-1.72-.91-2.53q.91-.842.91-2.595V9.311l3.75-3.75l.72.719q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243z");
}

</style>
