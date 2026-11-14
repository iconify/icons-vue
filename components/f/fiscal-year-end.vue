<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-1lmdpdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fiscal-year-end" /></template>
<style>
.b-1lmdpdo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.263 4.288q3.295-1.098 6.572.541q.094.047.171.117t.132.16t.083.189q.029.101.029.205v6q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.177 0-.335-.079q-2.465-1.232-4.915-.61V20.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-13q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h12.25V5q0-.177.079-.335q.067-.134.18-.232q.112-.097.254-.145m5.487 6.074V5.977q-2.256-.986-4.5-.416v4.46q2.254-.471 4.5.341");
}

</style>
