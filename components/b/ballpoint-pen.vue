<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1ip-2t-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ballpoint-pen" /></template>
<style>
.j1ip-2t-q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.846 7.404q0-1.346-.952-2.298t-2.298-.952t-2.298.952L7.934 11.47q-.952.952-.952 2.298t.952 2.298t2.298.952t2.298-.952l6.364-6.364q.952-.952.952-2.298M4.53 20.53l1.5-1.5q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.105-.106-.243-.163T5.5 17.75t-.287.057t-.243.163l-1.5 1.5q-.053.052-.094.113t-.069.13t-.043.141T3.25 20q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163T4 20.75t.287-.057t.243-.163");
}

</style>
