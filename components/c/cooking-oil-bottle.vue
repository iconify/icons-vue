<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxl2cebvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cooking-oil-bottle" /></template>
<style>
.jxl2cebvo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 2.75h-4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146V7q0 .281-.861 1.033Q6.25 9.902 6.25 12v7q0 2.75 2.75 2.75h6q2.75 0 2.75-2.75v-7q0-2.098-2.139-3.967Q14.75 7.281 14.75 7V3.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q14.074 2.75 14 2.75m-2.45 8.65q.048-.036.102-.064t.111-.048t.117-.028q.06-.01.12-.01t.12.01t.117.028q.058.02.111.048q.054.028.102.064q2.3 1.725 2.3 3.6q0 2.75-2.75 2.75T9.25 15q0-1.875 2.3-3.6m-.8 3.6q0 1.25 1.25 1.25T13.25 15q0-.965-1.25-2.04q-1.25 1.075-1.25 2.04");
}

</style>
