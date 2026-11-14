<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9rbj-knq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flat-roof" /></template>
<style>
.v9rbj-knq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 3.25h16q2.25 0 2.25 2.25q0 .932-.659 1.591q-.569.569-1.341.647V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-15q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V7.738q-.772-.078-1.341-.647Q1.75 6.432 1.75 5.5q0-2.25 2.25-2.25m10.25 17.5h4.5v-13H5.25v13h4.5V16.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h3q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146zM12 9H8.5q-2.25 0-2.25 2.25v.5q0 .932.659 1.591T8.5 14h7q.932 0 1.591-.659t.659-1.591v-.5Q17.75 9 15.5 9zm-.75 11.75h1.5v-3.5h-1.5z");
}

</style>
