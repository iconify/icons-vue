<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1flnpbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:airline-meal-tray" /></template>
<style>
.b1flnpbli {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 3.25H6.875q-2.123 0-3.624 1.501T1.75 8.375v7.25q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624v-7.25q0-2.123-1.501-3.624T17.125 3.25M13.5 9.499q.002-2.997 3-2.997t3 2.997V9.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.093.113q-.053.052-.114.093t-.13.07t-.14.043t-.146.014h-4.502q-.065 0-.129-.011q-.064-.012-.126-.034q-.061-.022-.117-.055q-.057-.032-.107-.074t-.092-.091t-.075-.106t-.056-.118t-.035-.125Q13.5 9.569 13.5 9.5zm3-1.497q1.059 0 1.37.748h-2.74q.311-.748 1.37-.748M4.75 12q0-3.75 3.75-3.75T12.25 12T8.5 15.75T4.75 12m10.047.539q.668-.789 1.703-.789t1.703.789q.669.79.499 1.81l-.298 1.788q-.269 1.613-1.904 1.613t-1.904-1.613l-.298-1.788q-.17-1.02.499-1.81");
}

</style>
