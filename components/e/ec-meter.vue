<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr_yo4bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ec-meter" /></template>
<style>
.gr_yo4bay {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 1.75h2q1.76 0 3.005 1.245T13.25 6v5q0 1.76-1.245 3.005T9 15.25h-.25v6.25q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T8 22.25t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-6.25H7q-1.76 0-3.005-1.245T2.75 11V6q0-1.76 1.245-3.005T7 1.75m.75 2.75Q5.5 4.5 5.5 6.75T7.75 9h.5q2.25 0 2.25-2.25T8.25 4.5zm10.819 8.512q3.181 3.711 3.181 5.488q0 3.75-3.75 3.75t-3.75-3.75q0-1.777 3.181-5.488q.048-.056.106-.102t.124-.079t.137-.053t.144-.026t.147.003t.144.032t.135.059t.12.085q.044.037.081.081M15.75 18.5q0-1.092 2.25-3.834q2.25 2.742 2.25 3.834q0 2.25-2.25 2.25t-2.25-2.25");
}

</style>
