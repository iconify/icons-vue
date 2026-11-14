<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smxy4mboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gym-mirror" /></template>
<style>
.smxy4mboh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 14.5V8q0-2.382 1.684-4.066T12 2.25t4.066 1.684T17.75 8v6.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146m6.22-7.78L9.22 9.97q-.053.052-.094.113t-.069.13t-.043.141T9 10.5t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l3.25-3.25q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.105-.106-.243-.163T13 6.5t-.287.057t-.243.163M9.75 18.5q0-2-2-2t-2 2v2q0 2 2 2t2-2v-.25h4.5v.25q0 2 2 2t2-2v-2q0-2-2-2t-2 2v.25h-4.5z");
}

</style>
