<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwimhsbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:budget-pie" /></template>
<style>
.cwimhsbrp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v9.189L4.72 18.22q-.081.08-.134.181t-.074.214q-.02.112-.007.225t.061.217Q1.75 16.112 1.75 12m3.193 7.434Q7.888 22.25 12 22.25q4.246 0 7.248-3.002T22.25 12t-3.002-7.248T12 1.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v8.75h8.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-9.189L5.78 19.28q-.105.106-.243.163t-.287.057q-.161 0-.307-.066");
}

</style>
