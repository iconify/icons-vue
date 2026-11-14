<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzmb4bchh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:low-emission-zone-sign" /></template>
<style>
.nzmb4bchh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.566 4.943Q1.75 7.888 1.75 12q0 4.246 3.002 7.248T12 22.25q4.112 0 7.057-2.816q-.104.047-.217.061t-.225-.007t-.214-.074t-.181-.134l-3.967-3.966Q11.845 17.25 7.5 17.25q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-4.345 1.936-6.753L4.72 5.78q-.081-.08-.134-.181t-.074-.214q-.02-.112-.007-.225t.061-.217m10.748 9.31Q17.25 11.845 17.25 7.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-4.345 0-6.753 1.936L5.78 4.72q-.08-.081-.181-.134t-.214-.074q-.112-.02-.225-.007t-.217.061Q7.888 1.75 12 1.75q4.246 0 7.248 3.002T22.25 12q0 4.112-2.816 7.057q.047-.104.061-.217t-.007-.225t-.074-.214t-.134-.181z");
}

</style>
