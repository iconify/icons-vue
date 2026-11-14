<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_p535bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arrow-right" /></template>
<style>
.v_p535bsg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.28 5.22l6.25 6.25q.106.105.163.243t.057.287t-.057.287t-.163.243l-6.25 6.25q-.105.106-.243.163T13.75 19t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T13 18.25t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l4.969-4.97H4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q3.25 12.074 3.25 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T4 11.25h14.189L13.22 6.28q-.053-.052-.094-.113t-.069-.13t-.043-.141T13 5.75t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.105-.106.243-.163T13.75 5t.287.057t.243.163");
}

</style>
