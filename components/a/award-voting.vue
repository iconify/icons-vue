<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jefprqhgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:award-voting" /></template>
<style>
.jefprqhgc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.75 10.256q1.6.083 2.755 1.239Q21.75 12.74 21.75 14.5V18q0 1.76-1.245 3.005T17.5 22.25h-11q-1.76 0-3.005-1.245T2.25 18v-3.5q0-1.76 1.245-3.005q1.155-1.156 2.755-1.239V3.5q0-1.75 1.75-1.75h8q1.75 0 1.75 1.75zm-10-.006h8.5V3.5q0-.25-.25-.25H8q-.25 0-.25.25zm3.5-2.811l-.97-.969q-.105-.106-.243-.163T9.75 6.25t-.287.057t-.243.163q-.053.052-.094.113t-.069.13t-.043.141T9 7t.014.146q.015.073.043.141t.069.13q.041.061.094.113l1.5 1.5q.105.106.243.163t.287.057t.287-.057t.243-.163l3-3q.053-.052.094-.113t.069-.13t.043-.141T15 5.5t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.105-.106-.243-.163t-.287-.057t-.287.057t-.243.163z");
}

</style>
